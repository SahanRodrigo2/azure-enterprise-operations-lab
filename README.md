# Azure Enterprise Operations Lab

## Project Overview

This project demonstrates the implementation of an enterprise Azure environment covering infrastructure, identity, monitoring, backup, alerting, and security controls.

## Technologies Used

* Microsoft Azure
* Windows Server 2025
* Active Directory Domain Services
* Ubuntu 24
* Apache Web Server
* Azure Monitor
* Log Analytics Workspace
* Recovery Services Vault
* Microsoft Defender for Cloud
* Network Security Groups
* Microsoft Entra ID

## Network Design

### Address Space

10.0.0.0/16

Why 10.0.0.0/16?

A large address space was selected to support future growth, scalability, and subnet segmentation.

### Subnets

Management-Subnet (10.0.1.0/24)

Purpose:
Administrative infrastructure and management resources.

Production-Subnet (10.0.2.0/24)

Purpose:
Application workloads and production services.

## Windows Server Implementation

* Windows Server 2025
* Active Directory Domain Services
* Domain Controller Deployment
* DNS Services

## Linux Server Implementation

* Ubuntu 24
* Apache Web Server
* Custom Enterprise Monitoring Lab Website

## Monitoring

Implemented:

* Azure Monitor
* Log Analytics Workspace
* VM Insights
* Heartbeat Monitoring
* CPU Monitoring

## Alerting

Implemented:

* High CPU Alert
* VM Offline Alert
* Low Disk Space Alert
* Action Groups

## Backup & Recovery

Implemented:

* Recovery Services Vault
* Daily Backup Policy
* Backup Validation
* Restore Testing

## Security

Implemented:

* Microsoft Defender for Cloud
* Secure Score Review
* Security Recommendations Review
* Network Security Groups
* Least Privilege Access Control

## Known Limitations

### Microsoft Entra ID

Unable to perform user/group administration due to tenant-level permission restrictions in Azure for Students environment.

Planned configuration:

* CloudAdmin
* CloudSupport
* Azure-Admins
* Azure-NOC

RBAC Design:

* Azure-Admins → Contributor
* Azure-NOC → Reader

### Azure Automation

Planned implementation:

* Get-AzureVMs Runbook
* Start-EnterpriseVMs Runbook
* Stop-EnterpriseVMs Runbook
* DailyShutdown Schedule

Deployment was not possible due to Azure for Students subscription restrictions affecting Azure Automation Accounts.

## Skills Demonstrated

* Azure Administration
* Windows Server Administration
* Linux Administration
* Azure Monitoring
* Log Analytics
* KQL Queries
* Backup and Recovery
* Security Hardening
* Network Security
* Incident Detection
* Troubleshooting

