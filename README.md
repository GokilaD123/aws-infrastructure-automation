# AWS Infrastructure Automation using Terraform

## Project Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform and automated server configuration using Ansible.

## Technologies Used
- AWS
- Terraform
- Ansible
- Git & GitHub
- Linux
- Apache Web Server

## Project Objectives
- Create AWS VPC and subnets using Terraform.
- Configure security groups and EC2 infrastructure.
- Automate web server configuration using Ansible.
- Manage project source code using Git and GitHub.

## Current Implementation
- Terraform configuration created and validated.
- Ansible playbook successfully executed on a local Ubuntu WSL environment.
- Apache web server verified using curl.
- Website content successfully served from localhost


## Project Status
AWS infrastructure deployment is not yet performed.

## How to Test Locally

### 1. Validate Terraform
```bash
cd terraform
terraform fmt -check
terraform init
terraform validate
```

### 2. Test Ansible

```bash
cd ../ansible
ansible-playbook playbook.yml --syntax-check
ansible-playbook playbook.yml -K
```

### 3. Verify Apache

```bash
curl http://localhost
```
