# Containers on Amazon ECS

Status: Planned — implementation has not started.

## Project objective

Run a containerized service on ECS and understand managed scheduling, networking, and service operations.

## Technologies

Amazon ECS, AWS Fargate, Amazon ECR, Application Load Balancer, IAM, CloudWatch

## Learning goals

- Understand task definitions, tasks, clusters, and services.
- Distinguish task roles from task execution roles.
- Operate a service using health checks, logs, scaling, and rollbacks.

## Prerequisites

- Complete 03-aws-vpc, 04-docker, and 07-cicd; Terraform knowledge is helpful.
- A working container image and AWS permissions for ECS and related services.
- Review Fargate, load balancer, registry, logging, and network costs.

## Implementation checklist

- [ ] Diagram the service and choose task resources and network placement.
- [ ] Push a versioned application image to ECR.
- [ ] Define task and execution roles, runtime configuration, and log collection.
- [ ] Create a task definition and service with appropriate security groups.
- [ ] Configure load balancing and health checks, then verify application access.
- [ ] Exercise an update, a rollback, and a scaling change; inspect events and logs.
- [ ] Document evidence and delete the service, load balancer, registry images, and other dedicated lab resources.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
