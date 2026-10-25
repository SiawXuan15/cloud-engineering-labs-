# Three-Tier Application

Status: Planned — implementation has not started.

## Project objective

Build and document an application with separate presentation, application, and data tiers.

## Technologies

Frontend and backend framework of your choice, relational database, Docker Compose, AWS EC2/VPC/RDS or a local equivalent

## Learning goals

- Define responsibilities and interfaces between three application tiers.
- Restrict database access and manage configuration and credentials.
- Validate end-to-end behavior and investigate failures across tiers.

## Prerequisites

- Complete 03-aws-vpc and 04-docker; complete 05-terraform for the AWS implementation.
- Choose an application language, database, and local or AWS deployment target.
- For AWS, estimate compute, database, storage, and networking charges.

## Implementation checklist

- [ ] Draw the architecture and define a minimal user workflow and acceptance criteria.
- [ ] Implement the frontend, backend API, and database schema yourself.
- [ ] Configure tier-to-tier connectivity and keep the database off public access paths.
- [ ] Supply secrets at runtime and document configuration without exposing values.
- [ ] Run schema setup and verify a complete create/read workflow.
- [ ] Test invalid input, unavailable dependencies, health checks, and persistent data.
- [ ] Record results and operational instructions; back up any needed lab data and clean up resources.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
