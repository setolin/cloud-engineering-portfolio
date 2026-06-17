# Azure Monitor Alert Plan

## Alerts to configure

1. VM High CPU
- Signal: Percentage CPU
- Threshold: > 80%
- Window: 5 minutes
- Action: Email notification

2. VM Availability
- Signal: VM availability metric or activity state
- Action: Investigate VM status

3. Storage Capacity / Transactions
- Signal: Storage account metrics
- Action: Review usage or abnormal activity

4. Administrative Activity
- Source: Azure Activity Log
- Action: Review role assignments and resource changes

## Documentation

For each alert:
- Alert name
- Scope
- Condition
- Action group
- Evidence screenshot
- Test result
- Triage notes
