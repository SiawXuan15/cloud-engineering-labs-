# Backup and Disaster Recovery

Status: Planned — implementation has not started.

## Project objective

Design and test a recovery procedure for an earlier application using disposable lab data.

## Technologies

Database backups, Amazon S3, EBS or RDS snapshots where applicable, Terraform, recovery runbooks

## Learning goals

- Define recovery time objective (RTO) and recovery point objective (RPO).
- Distinguish backup creation from proven recovery.
- Measure recovery results and identify dependencies and gaps.

## Prerequisites

- Complete 06-three-tier-app and 11-monitoring; AWS recovery exercises also require 05-terraform.
- Disposable test data, an isolated recovery environment, and backup/restore permissions.
- Estimate backup storage, transfer, and temporary recovery infrastructure costs.

## Implementation checklist

- [ ] Identify failure scenarios, dependencies, and target RTO and RPO.
- [ ] Choose backup frequency, retention, encryption, and access controls.
- [ ] Create a backup of disposable data and record its recovery point.
- [ ] Write a recovery runbook including infrastructure, configuration, secrets, and data dependencies.
- [ ] Simulate a lab failure and restore into an isolated recovery environment.
- [ ] Validate data integrity and application behavior; measure actual RTO and RPO against targets.
- [ ] Document gaps, repeat improvements as needed, and clean up recovery resources and unneeded lab backups.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
