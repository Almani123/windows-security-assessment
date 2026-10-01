# windows-security-assessment
Windows Security Assessment and Remediation – Arrowstack Project
# Windows Security Assessment and Remediation

## Project Overview

This project documents a Windows security assessment and remediation
workflow performed as part of the Arrowstack cybersecurity internship.

## Objectives

- Assess Windows local user accounts
- Review administrator group membership
- Verify Windows Firewall configuration
- Verify Microsoft Defender security status
- Document security validation results

## Technologies

- Windows 10/11
- PowerShell
- Windows Defender
- Windows Firewall

## Security Checks

### 1. Local User Accounts

Reviewed local Windows accounts and their enabled/disabled status.

### 2. Administrator Group

Reviewed members of the local Administrators group to assess
administrative access.

### 3. Windows Firewall

Verified that Domain, Private, and Public firewall profiles were enabled.

### 4. Microsoft Defender

Verified antivirus, antispyware, real-time protection, and
Microsoft Defender services.

## Validation Results

| Security Control | Status |
|---|---|
| Windows Firewall | Enabled |
| Microsoft Defender | Enabled |
| Guest Account | Disabled |
| Built-in Administrator | Disabled |
| Administrator Group | Reviewed |
| Local User Accounts | Reviewed |

## Evidence

Screenshots and supporting evidence are available in the
`screenshots` directory.

## Disclaimer

This project was performed in a controlled personal/lab Windows
environment for cybersecurity learning and assessment purposes.
