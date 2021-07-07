# AWS Foundation - CloudTrail

# Collect CloudTrail Data from S3
![Architecture](https://github.com/criblio/aws-quickstart-cribl-logstream/blob/main/architecture/cloudtrail_cf_template_design.png)

This quick link will enable a new CloudTrail (cribl-cloudtrail-sqs-s3-Trail-`<uniqueID>`), create an S3 bucket where the CloudTrail events will land. An SQS will also be created with the appropriate policy to allow events from S3 to be sent into this SQS: 
- [US East 1](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateUrl=https%3A%2F%2Fquickstart-cribl-logstream.s3.amazonaws.com%2Fcftemplates%2Fcloudtrail-s3%252Bsqs.yaml&stackName=cribl-cloudtrail-sqs-s3&param_CloudWatchLogsRetentionInDays=7&param_ExternalTrailBucket=&param_LogFilePrefix=&param_ParentAlertStack=&param_PermissionsBoundary=&param_S3DataEvents=true&param_SQS=cribl-sqs-cloudtrail)
- [US East 2](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/quickcreate?templateUrl=https%3A%2F%2Fquickstart-cribl-logstream.s3.amazonaws.com%2Fcftemplates%2Fcloudtrail-s3%252Bsqs.yaml&stackName=cribl-cloudtrail-sqs-s3&param_CloudWatchLogsRetentionInDays=7&param_ExternalTrailBucket=&param_LogFilePrefix=&param_ParentAlertStack=&param_PermissionsBoundary=&param_S3DataEvents=true&param_SQS=cribl-sqs-cloudtrail) 
- [US West 1](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/quickcreate?templateUrl=https%3A%2F%2Fquickstart-cribl-logstream.s3.amazonaws.com%2Fcftemplates%2Fcloudtrail-s3%252Bsqs.yaml&stackName=cribl-cloudtrail-sqs-s3&param_CloudWatchLogsRetentionInDays=7&param_ExternalTrailBucket=&param_LogFilePrefix=&param_ParentAlertStack=&param_PermissionsBoundary=&param_S3DataEvents=true&param_SQS=cribl-sqs-cloudtrail)
- [US West 2](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/quickcreate?templateUrl=https%3A%2F%2Fquickstart-cribl-logstream.s3.amazonaws.com%2Fcftemplates%2Fcloudtrail-s3%252Bsqs.yaml&stackName=cribl-cloudtrail-sqs-s3&param_CloudWatchLogsRetentionInDays=7&param_ExternalTrailBucket=&param_LogFilePrefix=&param_ParentAlertStack=&param_PermissionsBoundary=&param_S3DataEvents=true&param_SQS=cribl-sqs-cloudtrail)

### Setup CloudTrail Logs

[Setup CloudTrail Logs and S3 collection](https://github.com/criblio/aws-quickstart-cribl-logstream/blob/main/steps/cloudtrail.md)
