# Containerize an Application

Status: Planned — implementation has not started.

## Project objective

Package a small application you choose into a reproducible container and run a local multi-container environment.

## Technologies

Docker Engine or Docker Desktop, Dockerfile, Docker Compose, container networks and volumes

## Learning goals

- Explain images, containers, layers, and build context.
- Separate application configuration, persistent data, and image contents.
- Troubleshoot container startup, networking, and health.

## Prerequisites

- Complete 01-linux-networking.
- A working Docker environment and a small application to create or select yourself.
- Basic knowledge of the application language and its runtime.

## Implementation checklist

- [ ] Define the application behavior and local acceptance tests.
- [ ] Write a Dockerfile and .dockerignore; select and justify a base image.
- [ ] Build and run the image using a non-root user where feasible.
- [ ] Configure environment variables without baking secrets into the image.
- [ ] Add a dependency with Compose and test networking and persistent storage.
- [ ] Test health, logs, restart behavior, and failure recovery.
- [ ] Document build and run instructions, then remove lab containers and unneeded volumes or images.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
