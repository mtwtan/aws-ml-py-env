# Isolated Python 3 environment with Boto 3
## CloudFormation template

### Introduction
A CloudFormation template to create an isolated Python 3 environment with Boto 3 with an Amazon EC2 instance running Amazon Linux 2 using virtualenv

### How to use
- Create an S3 bucket to store your CloudFormation template or use an existing S3 bucket to do so
- Create or reuse an IAM role that has the appropriate policies to access all the relevant AWS services required
- Create or reuse a SSH key to use to access the EC2 instance

### Reference
- [AWS Link](https://aws.amazon.com/premiumsupport/knowledge-center/ec2-linux-python3-boto3/)