# AWS Infrastructure Automation using Terraform

## Overview
This project provisions a complete AWS environment using Terraform.

## Infrastructure Created
- Custom VPC
- 2 Public Subnets (Multi-AZ)
- Internet Gateway + Route Table
- Security Group (SSH, HTTP)
- EC2 instance (Ubuntu)
- S3 bucket (private, versioning enabled)

## Tools Used
- Terraform
- AWS (EC2, VPC, S3, IAM)
- WSL Ubuntu + VS Code

## How to Run
terraform init  
terraform plan  
terraform apply  
terraform destroy  

## Architecture
(attach architecture.png)
