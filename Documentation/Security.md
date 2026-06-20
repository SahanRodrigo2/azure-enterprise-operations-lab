# Security Implementation

## Microsoft Defender for Cloud

Reviewed:

* Security Posture
* Recommendations
* Secure Score

## Network Security

Network Security Group:
NSG-Enterprise

Configured Rules:

* Allow RDP (3389)
* Allow SSH (22)
* Allow HTTP (80)

## Microsoft Entra ID

Planned Configuration:

Users:

* CloudAdmin
* CloudSupport

Groups:

* Azure-Admins
* Azure-NOC

Implementation was limited by Azure for Students tenant-level permission restrictions.

## Azure Automation

Planned Implementation:

* Get-AzureVMs Runbook
* Start-EnterpriseVMs Runbook
* Stop-EnterpriseVMs Runbook
* DailyShutdown Schedule

Deployment was not possible due to Azure for Students subscription restrictions.

## Skills Demonstrated

* Security Hardening
* Network Security
* RBAC Design
* Security Monitoring
