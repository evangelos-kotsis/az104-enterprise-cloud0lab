# az104-enterprise-cloud-lab
Enterprise Azure Administrator lab for AZ-104 using Terraform, Entra ID, GitHub Actions, and Azure services.

This repository documents and implements an enterprise-style Azure Administrator lab for AZ-104 preparation.

The lab uses Microsoft Azure, Terraform, Microsoft Entra ID, GitHub Actions, and Azure monitoring services to simulate a real-world cloud environment.

## Objectives

- Build Azure infrastructure from the ground up
- Understand core AZ-104 concepts through hands-on implementation
- Use Terraform for Infrastructure as Code
- Store Terraform state remotely in Azure Storage
- Use GitHub Actions for CI/CD
- Implement identity and access management with Microsoft Entra ID
- Deploy a small application to Azure
- Document the full architecture and decisions

## Current Azure Environment

- Tenant: Default Directory
- Primary Domain: pafron83.onmicrosoft.com
- Subscription: Azure Subscription 1
- Plan: Azure Free Plan
- Primary Region: West Europe
- Resource Group: rg-az104-lab-dev

## Repository Structure

```text
docs/
terraform/
app/
.github/workflows/

| Phase | Topic                  | Status      |
| ----- | ---------------------- | ----------- |
| 01    | Azure Foundations      | In Progress |
| 02    | Resource Groups        | In Progress |
| 03    | Storage Account        | Not Started |
| 04    | Terraform Remote State | Not Started |
| 05    | Networking             | Not Started |
| 06    | Virtual Machines       | Not Started |
| 07    | Entra ID               | Not Started |
| 08    | App Service            | Not Started |
| 09    | CI/CD                  | Not Started |
| 10    | Monitoring             | Not Started |




