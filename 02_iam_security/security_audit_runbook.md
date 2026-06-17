# IAM Security Audit Runbook

## Purpose

Review access permissions in AWS and Azure to reduce unnecessary privilege and support secure cloud operations.

## AWS Checks

1. Confirm MFA is enabled for privileged accounts.
2. Review IAM users, groups and roles.
3. Identify policies with AdministratorAccess.
4. Check whether any policy allows "*" actions unnecessarily.
5. Review CloudTrail for recent administrative actions.
6. Use Access Analyzer where available.
7. Document risks and corrective actions.

## Azure Checks

1. Review Microsoft Entra ID users.
2. Review RBAC assignments at subscription, resource group and resource level.
3. Identify Owner or Contributor roles assigned too broadly.
4. Review Activity Log for administrative changes.
5. Confirm whether least-privilege role assignment is possible.
6. Document risks and corrective actions.

## Output

- Access review date
- Accounts reviewed
- Excessive access found
- Corrective action
- Evidence screenshots
- Remaining risk
