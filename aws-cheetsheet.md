# AWS Cheatsheet

## Core services
- **EC2** : virtual servers in the cloud
- **S3** : file and object storage
- **IAM** : users, roles, and permissions
- **VPC** : your private network in AWS
- **CloudWatch** : logs and monitoring

## AWS CLI commands
- `aws --version` : check the CLI is installed
- `aws configure` : save your access key and region
- `aws s3 ls` : list your S3 buckets
- `aws ec2 describe-instances` : list your EC2 servers
- `aws iam list-users` : list IAM users

## Good practices
- Never share or commit your access keys
- Give users only the permissions they need