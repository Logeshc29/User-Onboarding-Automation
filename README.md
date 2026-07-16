# User Onboarding Automation

## Architecture

Architecture.png

## Overview

This project automates user onboarding using:

- ServiceDesk Plus (SDP)
- Power Automate
- Azure Automation Runbook
- Microsoft Graph API

## Workflow

1. User onboarding request raised in SDP.
2. Ticket gets approved.
3. Power Automate triggers Azure Automation Runbook.
4. Runbook creates Microsoft 365 user.
5. License assigned automatically.
6. Security groups added.
7. Welcome email sent.
8. SDP ticket updated with status.

## Repository Structure

```text
Runbooks/
 └── Create-UserOnboarding.ps1

Architecture.md
Architecture.png
README.md
