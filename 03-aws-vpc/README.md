# AWS VPC Networking

Status: Planned — implementation has not started.

## Project objective

Design a segmented AWS network and explain how routing and security controls determine connectivity.

## Technologies

Amazon VPC, subnets, route tables, internet gateway, NAT gateway, security groups, network ACLs, VPC Flow Logs

## Learning goals

- Plan non-overlapping CIDR ranges and public versus private subnets.
- Trace inbound and outbound traffic through routes and gateways.
- Compare stateful security groups with stateless network ACLs.

## Prerequisites

- Complete 01-linux-networking and 02-aws-ec2.
- AWS permissions for networking and temporary test instances.
- Review NAT gateway, public IPv4, and logging costs before building.

## Implementation checklist

- [ ] Draw the network and allocate CIDR ranges across two Availability Zones.
- [ ] Create a VPC, public and private subnets, and explicit route table associations.
- [ ] Configure an internet gateway and explain what makes a subnet public.
- [ ] Plan private outbound access and decide whether paid NAT resources are needed for the lab.
- [ ] Apply least-privilege traffic rules and test allowed and denied connections.
- [ ] Use route inspection and flow logs to investigate a connectivity failure.
- [ ] Capture the final diagram and test results; remove test instances, gateways, logs, and remaining lab networking resources.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
