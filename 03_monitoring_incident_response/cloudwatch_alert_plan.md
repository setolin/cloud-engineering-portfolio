# AWS CloudWatch Alert Plan

## Alerts to configure

1. EC2 High CPU
- Metric: CPUUtilization
- Threshold: > 80%
- Period: 5 minutes
- Action: Email notification

2. EC2 Status Check Failed
- Metric: StatusCheckFailed
- Threshold: >= 1
- Period: 5 minutes
- Action: Email notification

3. S3 Bucket Size Growth
- Metric: BucketSizeBytes
- Threshold: project-defined
- Action: Review storage growth

4. IAM / CloudTrail Admin Activity
- Source: CloudTrail event history
- Action: Review administrative changes

## Documentation

For each alert:
- Name
- Resource
- Threshold
- Reason for threshold
- Expected response
- Screenshot
- Test result
