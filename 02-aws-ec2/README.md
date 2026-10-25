# AWS EC2 Fundamentals

Status: Planned — implementation has not started.

## Project objective

Provision and administer a small Linux virtual machine in AWS, documenting its access model and lifecycle.

## Technologies

Amazon EC2, Amazon EBS, IAM, security groups, SSH or AWS Systems Manager

## Learning goals

- Understand instance images, sizes, storage, and instance states.
- Distinguish IAM permissions from network access controls.
- Practice secure access, troubleshooting, and resource cleanup.

## Prerequisites

- Complete 01-linux-networking.
- An AWS account, an approved region, and an identity with scoped lab permissions.
- Review expected charges and establish a budget alert before provisioning.

## Implementation checklist

- [ ] Diagram the instance, storage, and access path; estimate lab cost.
- [ ] Choose an AMI and instance size and justify the choices.
- [ ] Define minimal security group rules and choose SSH or Systems Manager access.
- [ ] Launch and tag an instance, then verify administrative access.
- [ ] Inspect storage, system logs, and instance status checks.
- [ ] Practice stopping, starting, and diagnosing an access failure.
- [ ] Record sanitized evidence, then terminate the instance and remove unneeded volumes or other billable resources.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
