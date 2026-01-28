# Identity & Access Management (IAM) Hardening – User Account Review

## Executive Summary
This project focuses on Identity and Access Management (IAM) principles by reviewing local user accounts and group memberships on a Windows system. The objective is to understand and validate user privilege assignments and enforce the principle of least privilege. Evidence is documented using screenshots and verification steps.

## Objectives
- Review existing user accounts on a Windows system
- Identify administrator and standard user roles
- Validate security implications of privilege assignments
- Document findings using professional security terminology

## Environment
- Operating System: Windows 10 / Windows 11
- Tools Used: User Accounts Manager (netplwiz), Windows Settings
- Account Type: Local User Account

## Implementation (Step-by-Step)
1. Opened the Run dialog using **Windows + R**.
2. Entered the command:netplwiz
3. Reviewed the list of local user accounts.
4. Selected the active user account and opened **Properties**.
5. Navigated to the **Group Membership** tab.
6. Identified whether the user belonged to:
- Administrator group
- Standard User group
7. Analyzed privilege level based on group membership.

## Proof of Work
All screenshots validating the steps above are stored in the `/proof` directory, including:
- User account listing
- Group membership configuration

## Diagnostics & Corrective Learning
- No system errors were encountered.
- Security review focused on verification rather than modification.
- Privilege assignments were validated to ensure compliance with least-privilege principles.

## Security Impact
- Prevents excessive administrative privileges
- Reduces risk of privilege escalation
- Supports access control auditing and compliance requirements

## Lessons Learned
- User privilege review is a critical IAM task.
- Administrative access should be strictly limited.
- IAM validation improves overall system security posture.

## References
- Microsoft Documentation: User Accounts and Security Groups
- NIST SP 800-53 – Access Control Guidelines

