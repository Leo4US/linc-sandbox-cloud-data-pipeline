# Cost control and resource governance

This document describes how cloud resources are planned, monitored and controlled within the LINC Sandbox Cloud Data Pipeline.

Cost awareness and strict governance are core principles of this project, especially during pilot and educational phases.

---

## Guiding principles

The sandbox follows four fundamental principles regarding cloud usage:

1. educational efficiency over scale  
2. minimal resource allocation  
3. short-lived and supervised workloads  
4. continuous monitoring and shutdown policies  

The objective is to maximize learning outcomes while minimizing financial exposure.

---

## Resource usage strategy by stage

### Stage 1 — Theory and commands
- No cloud resources required
- Local execution only
- No associated cloud cost

### Stage 2 — Modeling and simulation
- Cloud architectures simulated locally
- Emulated object storage and services
- No consumption of cloud credits

### Stage 3 — Controlled practical execution
- Limited and pre-approved cloud services
- Small datasets and fixed quotas
- Short execution windows
- Manual supervision by project lead

Typical resources (example):
- object storage (small buckets)
- lightweight compute instances
- limited runtime environments

### Stage 4 — Partner challenge and hackathon
- Predefined service list and quotas
- Time-boxed execution (event-based)
- All resources created using templates
- Immediate teardown after the event

---

## Cost monitoring and safeguards

The following safeguards are applied:

- predefined spending limits
- real-time monitoring dashboards
- alerts for abnormal usage
- daily review during active periods
- immediate shutdown procedures

No open-ended or unsupervised workloads are allowed.

---

## Credit usage rationale

Requested cloud credits are intended exclusively for:

- supervised educational activities
- short-term experimental workloads
- partner-driven pilot challenges

They are not intended for:
- production systems
- continuous services
- commercial exploitation

---

## Accountability

All cloud usage is:
- documented
- attributable to specific activities
- reviewed by the project lead

This governance model ensures responsible use of cloud resources and alignment with educational and research objectives.
