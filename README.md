# CloudFormation VPC + EC2 + S3 Project

This project provisions AWS infrastructure using AWS CloudFormation.

## Resources Created

* VPC
* Internet Gateway
* Public Subnet
* Route Table
* Security Group
* EC2 Instance
* S3 Bucket

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/cloudformation-vpc-ec2-s3.git
cd cloudformation-vpc-ec2-s3
```

## Validate Template

```bash
aws cloudformation validate-template --template-body file://template.yaml
```

## Create Stack

```bash
aws cloudformation create-stack \
  --stack-name my-stack \
  --template-body file://template.yaml
```

## Check Stack Status

```bash
aws cloudformation describe-stacks --stack-name my-stack
```

## Delete Stack

```bash
aws cloudformation delete-stack --stack-name my-stack
```

## Architecture

Internet Gateway → Public Subnet → EC2 Instance

Additional Resources:

* VPC
* Security Group
* S3 Bucket

## Prerequisites

* AWS Account
* AWS CLI Configured
* CloudFormation Permissions

# Delete Stack
```
aws cloudformation delete-stack \
  --stack-name my-stack

## Author

Mrunal Patil

Cloud & DevOps Learner


```
