# Azure Terraform Deployment Guide

This README provides instructions for deploying the Softuni app in Azure using Terraform.

## Prerequisites
Before proceeding with the deployment, make sure you have the following:

- Git installed on your machine
- Azure subscription and appropriate permissions
- Terraform installed on your machine

## Deployment Steps

1. Clone the repository by running the following command in your terminal:
```bash
https://github.com/Antonio0512/Task-Board.git
```

2. Go to the cloned location:
```bash
cd Task-Board
```

3. 3. Initialize Terraform in the project directory by running the following command:
```bash
terraform init
```

4. Update the necessary configuration files to match your deployment requirements. There are four files that can be customized.

5. To ensure proper formatting and validate the configuration files, run the following commands:
```bash
terraform fmt
terraform validate
```


6. Deploy the app to Azure by running the following command:

You have to create the values.tfvars file before the apply command!
```bash
terraform apply -var-file="values.tfvars"
```

That is all!
