# Azure Capstone Project

## Overview
This project demonstrates a secure cloud infrastructure deployed on Microsoft Azure.

## Architecture
- 2 Linux Virtual Machines
- Azure SQL Database
- Azure Key Vault
- Virtual Network (VNet)
- Load Balancer

## Security
- Azure Key Vault used for storing secrets (credentials & connection strings)
- Role-Based Access Control (RBAC) implemented
- Least Privilege Principle applied
- No public access to database (private networking approach)

## Monitoring
- Azure Monitor enabled for VM monitoring
- CPU alert configured (threshold > 80%)
- Metrics collected for CPU, network, and disk usage

## Automation
- Infrastructure deployed using ARM Template exported from Azure Portal
- All resources defined in template.json

## Files
- template.json → Infrastructure as Code (ARM template)

## Author
Capstone Project Deployment
