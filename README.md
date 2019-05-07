# ![LOGO](logo.png) HDInsightJobManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the HDInsightJobManagementClient API (version 2018-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/hdinsight-job/2018-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:13+03:00

## API Description

The HDInsight Job Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Submits a Hive job to an HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.

### Gets the list of jobs from the specified HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.
* `showall` - _required_ - If showall is set to 'true', the request will return all jobs the user has permission to view, not only the jobs belonging to the user.
    Possible values: true.
* `fields` - _required_ - If fields set to '*', the request will return full details of the job. Currently the value can only be '*'.
    Possible values: *.

### Initiates cancel on given running job in the specified HDInsight.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.
* `jobId` - _required_ - The id of the job.

### Gets job details from the specified HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.
* `jobId` - _required_ - The id of the job.
* `fields` - _required_ - If fields set to '*', the request will return full details of the job. Currently the value can only be '*'.
    Possible values: *.

### Gets numrecords Of Jobs after jobid from the specified HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.
* `jobid` - _optional_ - JobId from where to list jobs.
* `numrecords` - _optional_ - Number of jobs to fetch.
* `showall` - _required_ - If showall is set to 'true', the request will return all jobs the user has permission to view, not only the jobs belonging to the user.
    Possible values: true.
* `fields` - _required_ - If fields set to '*', the request will return full details of the job. Currently the value can only be '*'.
    Possible values: *.

### Submits a MapReduce job to an HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.

### Submits a MapReduce streaming job to an HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.

### Submits a Pig job to an HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.

### Submits a Sqoop job to an HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `user.name` - _required_ - The user name used for running job.

### Gets application state from the specified HDInsight cluster.

*Tags:* `Job`

#### Input Parameters
* `appId` - _required_ - The id of the job.

## License

**flow**ground :- Telekom iPaaS / azure-com-hdinsight-job-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
