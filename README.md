# Terraform AWS EC2

Provisions a real EC2 instance on AWS using Terraform.

## Stack
- Terraform
- AWS EC2
- AWS CLI

## What it does
Creates a t3.micro EC2 instance (free tier eligible) in us-east-1
tagged as devops-portfolio-server — entirely from code, no clicking
in the AWS Console.

## Usage
terraform init
terraform plan
terraform apply

To destroy:
terraform destroy

## Important
Always run terraform destroy after testing to avoid AWS charges.# terraform-aws-ec2
