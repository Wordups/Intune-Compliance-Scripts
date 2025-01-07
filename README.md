# Intune-Compliance-Scripts
"PowerShell scripts for automating compliance reporting and policy enforcement in Microsoft Intune."
# PowerShell Scripts for Intune Compliance Reporting

## Overview
This repository contains PowerShell scripts designed to automate compliance reporting and policy enforcement in Microsoft Intune. These scripts help streamline IT operations and improve visibility into device compliance.

## Key Features
- **Automated Compliance Reports**:
  - Scripts to generate detailed compliance reports for devices enrolled in Intune.
- **Policy Audit Automation**:
  - Verify that all devices meet encryption, OS version, and security baselines.
- **Integration with Monitoring Tools**:
  - Export compliance data for integration with tools like Splunk or Microsoft Power BI.
- **Custom Alerts**:
  - Notify administrators of non-compliant devices via email or Teams.

## Scripts Included
- **ComplianceReport.ps1**:
  - Generates a CSV report of all devices and their compliance status.
- **PolicyAudit.ps1**:
  - Audits devices against specific compliance policies.
- **NonComplianceAlerts.ps1**:
  - Sends alerts for non-compliant devices via email or Teams.

## Setup Guide
1. **Prerequisites**:
   - Install the `Microsoft.Graph.Intune` PowerShell module.
   - Ensure proper permissions are granted in Azure AD for running Intune-related commands.
2. **Clone the Repository**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/Wordups/Intune-Compliance-Scripts.git
     ```
3. **Run the Scripts**:
   - Use `ComplianceReport.ps1` to generate compliance reports:
     ```bash
     ./ComplianceReport.ps1 -ExportPath "C:\Reports\Compliance.csv"
     ```
   - Use `PolicyAudit.ps1` to check compliance with specific policies:
     ```bash
     ./PolicyAudit.ps1 -PolicyName "Device Encryption"
     ```

## Results
- Reduced manual compliance checks by 50%.
- Improved reporting accuracy for audits and compliance tracking.
- Enhanced visibility into device compliance with automated alerts.

## Screenshots
*(Add screenshots of PowerShell outputs, sample reports, or integration dashboards here.)*

## Technologies Used
- Microsoft Intune
- Azure AD
- PowerShell
- Microsoft Graph API

## Next Steps
- Expand scripts to include advanced policy enforcement workflows.
- Integrate PowerShell scripts with Microsoft Power Automate for real-time compliance monitoring.
