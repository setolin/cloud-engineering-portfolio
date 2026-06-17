# Azure RBAC Notes — Least-Privilege Model

## Suggested roles for the lab

Owner:
- Only used by the primary administrator account.
- Not used for daily support tasks.

Reader:
- Used for basic visibility during troubleshooting.
- Suitable for junior support review tasks.

Monitoring Reader:
- Used for monitoring dashboards, metrics and alerts.
- Suitable for incident triage without allowing infrastructure changes.

Storage Blob Data Reader:
- Used for read-only storage validation.
- Avoids unnecessary write/delete access.

Virtual Machine Contributor:
- Use only when VM operational actions are required.
- Avoid assigning at subscription level if resource-group scope is enough.

## Evidence to document

- Role assignment scope
- Reason why each role was selected
- Risk if excessive permissions were granted
- Screenshot of role assignment
- Screenshot of activity log after access test
