# Monitoring and Observability

Status: Planned — implementation has not started.

## Project objective

Instrument an earlier application and use metrics, logs, and alerts to detect and investigate failures.

## Technologies

Amazon CloudWatch or Prometheus and Grafana, application logs, metrics, dashboards, alerting

## Learning goals

- Distinguish metrics, logs, and traces and identify useful operational signals.
- Define measurable service objectives and actionable alerts.
- Use evidence to investigate an incident and improve a runbook.

## Prerequisites

- A running application from 06-three-tier-app, 08-aws-ecs, 09-kubernetes, or 10-aws-eks.
- Choose a local or AWS monitoring stack and access to its configuration.
- Review telemetry retention, ingestion, and notification costs if using hosted services.

## Implementation checklist

- [ ] Choose service indicators and define a measurable availability or latency objective.
- [ ] Collect application and infrastructure metrics and structured logs.
- [ ] Create a dashboard covering traffic, errors, latency, and resource saturation.
- [ ] Configure alert thresholds and a test notification destination you control.
- [ ] Generate a controlled error or resource pressure and verify detection.
- [ ] Follow and refine a runbook; record detection and recovery times.
- [ ] Save sanitized dashboard evidence and remove lab alerts, monitoring services, and unneeded stored telemetry.

## Portfolio evidence

As you implement this project, add your architecture diagram, setup and validation instructions, sanitized screenshots or command output, troubleshooting notes, and lessons learned. Record design tradeoffs and cleanup results. Keep credentials, private keys, real customer data, and sensitive state out of the repository.

[Back to learning roadmap](../README.md)
