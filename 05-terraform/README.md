# Infrastructure as Code with Terraform

Status: Planned — implementation has not started.

## Project objective

Describe a small AWS environment as code and practice a reviewable infrastructure lifecycle.

## Technologies

Terraform, AWS provider, variables, outputs, state, remote backend

## Learning goals

- Understand configuration, plan, apply, drift, and destroy.
- Use variables and outputs to make infrastructure reusable.
- Protect state and explain collaboration and state locking.

## Prerequisites

- Complete 02-aws-ec2 and 03-aws-vpc.
- Terraform and authenticated AWS access with scoped permissions.
- Choose a small lab scope and review its cost before applying.

## Implementation checklist

- [ ] Define the resources and write a diagram before creating configuration.
- [ ] Declare Terraform and provider version constraints and configure variables and outputs.
- [ ] Run formatting and validation, then inspect a plan before applying it yourself.
- [ ] Verify the provisioned resources and compare them with the plan.
- [ ] Introduce a controlled change and observe drift and reconciliation.
- [ ] Document local versus remote state, access controls, and locking; configure a backend if appropriate.
- [ ] Destroy lab resources, verify cleanup, and keep state and secrets out of Git.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
