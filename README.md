# cloud-engineering-labs-

A hands-on Cloud Engineering learning portfolio, progressing from Linux and networking to cloud infrastructure, containers, delivery automation, operations, and recovery.

This repository starts with project guides only. All projects are **planned**, and the checklists are intentionally unchecked so I can implement each project myself while learning.

## Learning roadmap

Work through the projects in order for the full curriculum. Start with Linux and AWS networking, then build container and infrastructure skills before integrating an application and delivery pipeline. Learn ECS and Kubernetes before tackling EKS, then add monitoring and recovery and bring the work together in a capstone.

| Step | Project | Focus | Status |
| --- | --- | --- | --- |
| 01 | [Linux and Networking Fundamentals](01-linux-networking/README.md) | Linux administration and connectivity troubleshooting | Planned |
| 02 | [AWS EC2 Fundamentals](02-aws-ec2/README.md) | Virtual machines, storage, and secure access | Planned |
| 03 | [AWS VPC Networking](03-aws-vpc/README.md) | Subnets, routing, and network boundaries | Planned |
| 04 | [Containerize an Application](04-docker/README.md) | Reproducible containers and local services | Planned |
| 05 | [Infrastructure as Code with Terraform](05-terraform/README.md) | Declarative infrastructure and state management | Planned |
| 06 | [Three-Tier Application](06-three-tier-app/README.md) | Presentation, application, and data tiers | Planned |
| 07 | [Continuous Integration and Delivery](07-cicd/README.md) | Automated validation, builds, and releases | Planned |
| 08 | [Containers on Amazon ECS](08-aws-ecs/README.md) | Managed container services on AWS | Planned |
| 09 | [Kubernetes Fundamentals](09-kubernetes/README.md) | Local orchestration and workload operations | Planned |
| 10 | [Managed Kubernetes on Amazon EKS](10-aws-eks/README.md) | Managed Kubernetes on AWS | Planned |
| 11 | [Monitoring and Observability](11-monitoring/README.md) | Metrics, logs, dashboards, and alerts | Planned |
| 12 | [Backup and Disaster Recovery](12-disaster-recovery/README.md) | Backups, restoration, and recovery objectives | Planned |
| 13 | [Cloud Engineering Capstone](13-capstone/README.md) | An integrated cloud application platform | Planned |

## How I will use this portfolio

1. Read a project's objective, learning goals, and prerequisites before starting.
2. Choose a small lab scope, draw the design, and review costs before creating cloud resources.
3. Implement the project myself and check off steps only after validating them.
4. Add reproducible setup instructions, sanitized evidence, troubleshooting notes, and lessons learned to its README.
5. Clean up temporary resources, record the result, and update the roadmap status when the work is complete.

The three-tier application can begin locally. ECS and EKS provide alternative cloud deployment tracks; the capstone can use either. Each project guide lists its specific prerequisites.

## Repository practices

- Keep application code and supporting artifacts inside the relevant project folder as they are created.
- Commit only sanitized examples of configuration. Keep real credentials, private keys, local environment files, and Terraform state out of Git.
- Commit Terraform dependency lock files for reproducible provider selection. Use sanitized `*.tfvars.example` files for example inputs.
- Treat `.gitignore` as a convenience, not a secret scanner: review every staged change before any future commit.
- Use disposable lab data and scoped permissions. Review current AWS pricing before provisioning; budget alerts do not cap spending.
- Stop or delete lab resources when finished and verify related storage, networking, logs, and backups are also handled.
