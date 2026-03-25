# Hybrid Environment Foundations And Management

## Overview
This project demonstrates the build, validation, and troubleshooting of a hybrid environment integrating on-prem Active Directory with Microsoft Entra ID.

It focuses on how objects and systems are synchronized, represented, and managed across both environments, with emphasis on determining source of authority, validating consistency, and resolving issues between on-prem and cloud systems.

The lab reflects real-world support scenarios where issues must be traced across multiple systems, including cases where changes are made in the wrong location or where sign-in behavior differs between environments. It demonstrates the ability to identify where issues originate, make correct management decisions for synced vs cloud-only users, and troubleshoot inconsistencies between Active Directory and Entra.

All configurations and findings were validated through direct comparison of system and object data, command-line verification, and cross-environment testing using a domain-joined workstation (W11VM). The project follows an evidence-first approach, with documented build validation, troubleshooting scenarios, tickets, and runbooks aligned to real IT support workflows.

## Work Performed
- Compared user objects between Active Directory and Microsoft Entra across synced and cloud-only accounts  
- Validated object attributes using Active Directory Users and Computers (ADUC) and the Entra Admin Center  
- Identified source of authority and determined correct management location  
- Investigated User Principal Name (UPN) differences and evaluated sign-in behavior  
- Verified device state using workstation W11VM  
- Performed cross-environment troubleshooting to determine whether issues originated in Active Directory or Entra  

## Start Here
Recommended files and folders to review first:

- [04-Ticket-Pack](./04-Ticket-Pack/)
- [03-Runbook](./03-Runbook/)
- [06-Resume-and-Interview](./06-Resume-and-Interview/)

## Skills Demonstrated
- Hybrid environment behavior across Active Directory and Microsoft Entra ID  
- Source of authority identification for synced and cloud-managed identities  
- Object and account validation across on-prem and cloud environments  
- User Principal Name (UPN) comparison and sign-in troubleshooting  
- Device state validation and join state interpretation  
- Differentiation between object representation and management boundaries  
- Structured troubleshooting and documentation practices  

## Project Structure
- [00-Project-Summary](./00-Project-Summary/) — overview and navigation  
- [01-Build-Evidence](./01-Build-Evidence/) — system and object validation and hybrid concept proof  
- [02-Troubleshooting-Evidence](./02-Troubleshooting-Evidence/) — raw notes, screenshots, and observations  
- [03-Runbook](./03-Runbook/) — reusable hybrid environment troubleshooting procedures  
- [04-Ticket-Pack](./04-Ticket-Pack/) — polished ticket write-ups  
- [05-PowerShell](./05-PowerShell/) — command outputs and validation artifacts  
- [06-Resume-and-Interview](./06-Resume-and-Interview/) — project packaging for job search  