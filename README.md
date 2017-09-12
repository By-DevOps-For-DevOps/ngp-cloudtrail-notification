# ngp-cloudtrail-notification
Slack Notification from AWS Cloudtrail

We can create AWS Alarms based on logs putout by AWS CloudTrail.AWS Documentation can be found here http://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudwatch-alarms-for-cloudtrail.html. 

## What we do here
Create a Cloudwatch alarm to monitor the list required Cloutrail messages and notify using Slack. Example is to monitor Codepipeline changes.
