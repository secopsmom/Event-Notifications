# Event Notifications
This stack was created using Event Rules based on CIS AWS Benchmarks. CloudWatch Alarms are delayed and require you to login to the AWS console, and delayed events are missed events. Using CloudWatch Event rules provides near real time alerts via SNS on activity within your account. 
## Setup
Using CloudFormation, you can deploy this stack to 1 account. For more effective coverage, consider using StackSets from a central account. IAM Role / Policy should only be deployed once to an account. Rest of the stack can be deployed regionally from there.
## Links
[AWS GitHub Repo](https://github.com/awslabs/aws-security-benchmark)
