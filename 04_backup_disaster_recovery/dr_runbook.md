# Disaster Recovery Runbook — Cloud Lab

## Purpose

Restore cloud lab resources after failure or accidental deletion.

## Scope

- AWS EC2 / EBS
- AWS S3
- Azure VM
- Azure Storage
- Configuration documentation

## Pre-Recovery Checks

1. Confirm affected resource.
2. Confirm last known healthy state.
3. Identify available backup or snapshot.
4. Confirm RPO/RTO target.
5. Document approval or reason for recovery test.

## AWS Recovery Steps

1. Review AWS Backup or EBS snapshot availability.
2. Select correct recovery point.
3. Restore volume or instance depending on the scenario.
4. Validate network/security group settings.
5. Confirm instance availability.
6. Test access and basic functionality.
7. Document result.

## Azure Recovery Steps

1. Open Recovery Services Vault.
2. Identify protected VM.
3. Select recovery point.
4. Restore VM or disk according to test scenario.
5. Validate NSG and network configuration.
6. Confirm VM availability.
7. Document result.

## Post-Recovery Validation

- Resource restored
- Access confirmed
- Data integrity checked
- Monitoring active
- Cost impact reviewed
- Lessons learned recorded
