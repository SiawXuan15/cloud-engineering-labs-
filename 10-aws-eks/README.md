# Managed Kubernetes on Amazon EKS

Status: Planned — implementation has not started.

## Project objective

Apply Kubernetes fundamentals to an AWS-managed cluster and document its identity and networking model.

## Technologies

Amazon EKS, IAM, VPC, managed node groups, kubectl, Amazon ECR, CloudWatch, Terraform

## Learning goals

- Distinguish AWS-managed control plane responsibilities from workload and node responsibilities.
- Understand cluster access and scoped AWS permissions for workloads.
- Evaluate cluster capacity, application exposure, and operational costs.

## Prerequisites

- Complete 03-aws-vpc, 05-terraform, and 09-kubernetes.
- AWS permissions for EKS and its supporting IAM and networking resources.
- Review ongoing cluster, worker, storage, load balancer, and network charges.

## Implementation checklist

- [ ] Design cluster subnets, endpoint access, node capacity, and identity controls.
- [ ] Provision a small cluster and compute capacity using infrastructure as code.
- [ ] Configure authorized kubectl access and inspect nodes and core components.
- [ ] Deploy a versioned application image and expose it through a deliberate access path.
- [ ] Configure scoped workload identity if the application needs AWS access.
- [ ] Validate probes, logs, scaling, and a rolling update; record troubleshooting steps.
- [ ] Delete workloads and their load balancers or volumes before tearing down the cluster and dedicated infrastructure; verify cleanup.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
