# Terraform Azure Infrastructure ☁️

## Overview
Azure cloud infrastructure provisioned with Terraform IaC.
Deploys a complete environment including VNet, Subnet, and Linux VM.

## Architecture
Terraform → Azure Resource Group → VNet → Subnet → VM

## Resources Created
- Resource Group
- Virtual Network (VNet)
- Subnet
- Public IP
- Network Interface
- Linux Virtual Machine (Ubuntu 18.04)

## Tech Stack
- Terraform — Infrastructure as Code
- Microsoft Azure — Cloud Provider
- Azure CLI — Authentication

## How to Use
# Install Terraform
sudo apt install terraform

# Login to Azure
az login

# Initialize Terraform
terraform init

# Preview changes
terraform plan

# Apply infrastructure
terraform apply

# Destroy infrastructure
terraform destroy

## Author
Asma Slimani — Junior DevOps Engineer
LinkedIn : https://www.linkedin.com/in/asma-slimani-4a732a296/
GitHub   : https://github.com/AsmaSlimanii
