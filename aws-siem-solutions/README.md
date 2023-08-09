## Infrastructure monitoring with ##
Guardduty: Cloudtrail logs,VPC Flow logs,DNS logs >>> are all generated automatically through guardduty 

Operating system logs: These logs can be forwarded to an s3 bucket and Athena can be used to run queries, also these logs can also forwarded to Cloudwatch Logs Insight or third party solutions like Splunk.

AWS Config rules. Used to monitor changes in security groups, new Instance Lauch and also route tables addition.

Amazon Instances: focuses on EC2 instances vulnerabilities: By detcting vulnerable OS libraries
Unencrypted network traffic unused TCP listeners

## Application Security Monitoring ##
CloudWatch logs contains logs coming in from;   Lambda Execution, EC2 Application, ECS/EKS Container logs.

Cloudtrail logs can also be used for logging events from;   Cognito User Authentication logs, Step Functions, Deployments via CodeDeploy.

## Account Security Montoring ##
CloudWatch Events can be collected from the Guarduty Findings, Cloudtrail Events, AWS Organizations

AWS Config rules can determined whether Cloudtrail was been enabled, IAM User Key has been rotated or whether there are rotations in place the Root User MFA is enabled
