# Hybrid Identity Foundations And Source Of Authority

## Overview
This project demonstrates the build, validation, and troubleshooting of a hybrid identity environment integrating on-prem Active Directory with Microsoft Entra ID.

It focuses on how identities are synchronized, represented, and managed across both environments, with emphasis on determining source of authority, validating identity consistency, and resolving issues between on-prem and cloud identity systems.

The lab reflects real-world support scenarios where identity issues must be traced across multiple systems, including cases where changes are made in the wrong location or where sign-in behavior differs between environments. It demonstrates the ability to identify where identity issues originate, make correct management decisions for synced vs cloud-only users, and troubleshoot inconsistencies between Active Directory and Entra.

All configurations and findings were validated through direct comparison of identity data, command-line verification, and cross-environment testing using a domain-joined workstation (W11VM). The project follows an evidence-first approach, with documented build validation, troubleshooting scenarios, tickets, and runbooks aligned to real IT support workflows.

## Work Performed
- Compared user identity between Active Directory and Microsoft Entra across synced and cloud-only accounts  
- Validated identity attributes using Active Directory Users and Computers (ADUC) and the Entra Admin Center  
- Identified source of authority and determined correct management location  
- Investigated User Principal Name (UPN) differences and evaluated sign-in behavior  
- Verified device identity state using workstation W11VM  
- Performed cross-environment troubleshooting to determine whether issues originated in Active Directory or Entra  

## Start Here
Recommended files and folders to review first:

- [04-Ticket-Pack](./04-Ticket-Pack/)
- [03-Runbook](./03-Runbook/)
- [06-Resume-and-Interview](./06-Resume-and-Interview/)

## Skills Demonstrated
- Hybrid identity behavior across Active Directory and Microsoft Entra ID  
- Source of authority identification for synced and cloud-managed identities  
- Identity validation across on-prem and cloud environments  
- User Principal Name (UPN) comparison and sign-in troubleshooting  
- Device identity validation and join state interpretation  
- Differentiation between identity representation and identity management  
- Structured troubleshooting and documentation practices  

## Project Structure
- [00-Project-Summary](./00-Project-Summary/) — overview and navigation  
- [01-Build-Evidence](./01-Build-Evidence/) — identity validation and hybrid concept proof  
- [02-Troubleshooting-Evidence](./02-Troubleshooting-Evidence/) — raw notes, screenshots, and observations  
- [03-Runbook](./03-Runbook/) — reusable hybrid identity troubleshooting procedures  
- [04-Ticket-Pack](./04-Ticket-Pack/) — polished ticket write-ups  
- [05-PowerShell](./05-PowerShell/) — command outputs and validation artifacts  
- [06-Resume-and-Interview](./06-Resume-and-Interview/) — project packaging for job search  