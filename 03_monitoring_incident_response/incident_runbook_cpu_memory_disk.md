# Incident Runbook — High CPU / Memory / Disk Pressure

## Incident Type

Resource pressure affecting cloud compute instance or virtual machine.

## Symptoms

- High CPU alarm triggered
- Application latency
- VM or instance slow response
- Increased error rates
- Disk utilisation warning

## First Response

1. Confirm alert source.
2. Check affected resource name and region.
3. Review metric history.
4. Check recent changes.
5. Confirm whether this is recurring or new.
6. Check logs for errors.
7. Escalate if production impact is suspected.

## AWS Investigation

1. Open CloudWatch.
2. Review EC2 CPUUtilization.
3. Check StatusCheckFailed metrics.
4. Review system logs if available.
5. Confirm security group/network changes.
6. Check recent CloudTrail events.

## Azure Investigation

1. Open Azure Monitor.
2. Review VM metrics.
3. Check Activity Log for changes.
4. Review Log Analytics if configured.
5. Confirm NSG/network changes.
6. Validate VM status.

## Corrective Actions

- Restart non-production test VM if approved.
- Resize instance/VM only after documented approval.
- Remove unnecessary process after investigation.
- Escalate to infrastructure owner if root cause is unclear.
- Document timeline and actions.

## Post-Incident Review

- What triggered the alert?
- Was the threshold correct?
- Was the runbook clear?
- Did the issue recur?
- What prevention action is required?
