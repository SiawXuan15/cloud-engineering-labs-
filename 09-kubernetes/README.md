# Kubernetes Fundamentals

Status: Planned — implementation has not started.

## Project objective

Run an application on a local Kubernetes cluster and learn its core workload and networking objects.

## Technologies

Kubernetes, kubectl, kind or minikube, Deployments, Services, ConfigMaps, Secrets, persistent volumes

## Learning goals

- Explain declarative reconciliation and Kubernetes object relationships.
- Configure health probes and resource requests and limits.
- Debug scheduling, networking, and application failures.

## Prerequisites

- Complete 01-linux-networking and 04-docker.
- A local container runtime, kubectl, and kind or minikube.
- Sufficient local CPU and memory for a small cluster.

## Implementation checklist

- [ ] Create a local cluster and inspect its nodes and system workloads.
- [ ] Write application Deployment and Service manifests in a dedicated namespace.
- [ ] Externalize configuration and handle secrets without committing real values.
- [ ] Add readiness and liveness probes and resource requests and limits.
- [ ] Test service discovery and persistence if the application requires storage.
- [ ] Practice scaling, rolling updates, rollback, and troubleshooting with events and logs.
- [ ] Document manifests and observations, then delete the lab namespace and local cluster.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
