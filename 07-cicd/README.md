# Continuous Integration and Delivery

Status: Planned — implementation has not started.

## Project objective

Automate checks, builds, and a controlled delivery workflow for an earlier application project.

## Technologies

GitHub Actions, Git, Docker, container registry, GitHub environments, AWS OIDC if deploying to AWS

## Learning goals

- Distinguish continuous integration, delivery, and deployment.
- Design useful checks and identify build artifacts consistently.
- Limit workflow permissions and plan release rollback.

## Prerequisites

- Complete 04-docker and have an application with meaningful tests, such as 06-three-tier-app.
- Access to configure Actions and a chosen artifact or container registry.
- Choose a delivery target; AWS deployment additionally requires appropriate permissions and a cost review.

## Implementation checklist

- [ ] Define pull-request checks, release triggers, and success criteria.
- [ ] Write a workflow for application tests, linting, and container builds.
- [ ] Use minimal workflow permissions and pin external actions to reviewed versions or commits.
- [ ] Publish versioned images or artifacts without including secrets.
- [ ] Configure environment controls and short-lived OIDC credentials if using AWS.
- [ ] Exercise a failed check and a controlled release; document a rollback procedure.
- [ ] Save sanitized workflow evidence and remove temporary deployments and unneeded artifacts.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
