# User Onboarding Automation

## Overview

Automates employee onboarding using:

- ServiceDesk Plus (SDP)
- Power Automate
- Azure Automation Runbook
- Microsoft Graph API

## Process Flow

1. User onboarding request raised in SDP.
2. Approval completed.
3. Power Automate triggers Azure Runbook.
4. Runbook creates M365 account.
5. License assigned.
6. Groups assigned.
7. Welcome email sent.
8. SDP ticket updated.

## Technologies Used

- Power Automate
- Azure Automation
- PowerShell
- Microsoft Graph API
- ServiceDesk Plus
