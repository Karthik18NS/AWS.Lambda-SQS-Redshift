# AWS.Lambda-SQS-Redshift

Scheduled an AWS Lambda function to trigger using AWS EventBridge to generate mock data and store it in an AWS SQS topic. Then, created an AWS Glue job to read the incremental data from SQS topic consumer and store the new records in Redshift.
