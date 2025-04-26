# Terraform Projects

This repository contains Terraform configurations for setting up cloud infrastructure (AWS, Azure, GCP, etc.).

## Structure
- `environments/` : Environment-specific Terraform code (dev, prod, staging).
- `modules/` : Reusable Terraform modules (VPC, EC2, RDS, etc.).
- `scripts/` : Helper scripts to automate Terraform commands.

## Requirements
- Terraform v1.x
- Cloud CLI installed (AWS CLI, Azure CLI, etc.)

## Basic Commands
Initialize Terraform:
```bash
terraform init
