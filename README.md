# Terraform Azure Availability Set

## Overview

This project creates an Azure Availability Set using Terraform.

Availability Set helps improve application availability by distributing Virtual Machines across different fault domains and update domains.

## Resources Created

* Resource Group
* Availability Set

## Project Structure

```text
15-terraform-azure-availability-set-simple/
│
├── main.tf
├── provider.tf
├── .gitignore
└── README.md
```

## Prerequisites

* Terraform installed
* Azure account
* Azure CLI installed

## Login to Azure

```bash
az login
```

## Initialize Terraform

```bash
terraform init
```

## Validate Terraform Configuration

```bash
terraform validate
```

## Generate Terraform Plan

```bash
terraform plan
```

## Deploy Infrastructure

```bash
terraform apply -auto-approve
```


## Availability Set Configuration

* Platform Fault Domain Count: 2
* Platform Update Domain Count: 5
* Managed Availability Set: Enabled

## Benefits of Availability Set

* Improves application uptime
* Protects against hardware failures
* Minimizes downtime during Azure maintenance
* Distributes VMs across multiple fault and update domains

## Author

Ranjeet Kumar
