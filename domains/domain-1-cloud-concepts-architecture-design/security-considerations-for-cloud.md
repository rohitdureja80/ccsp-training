# Security Considerations for Cloud

**Domain:** 1 - Cloud Concepts, Architecture & Design  
**Priority:** 🔴 Critical  
**Exam Frequency:** ⭐⭐⭐⭐⭐

## Overview

Cloud security design must account for risks introduced by virtualization, multi-tenancy, remote access, elastic resources, and distributed infrastructure.

## Data Location, Residency, and Sovereignty

| Concept | Meaning |
|---|---|
| Data Location | Where data physically or logically resides. |
| Data Residency | Requirement that data remain in a specific geography. |
| Data Sovereignty | Data is subject to the laws of the country where it is located. |

## Isolation and Multi-Tenancy

Cloud environments depend on logical isolation between tenants.

Risks include:
- Weak tenant isolation
- Misconfigured access controls
- Side-channel attacks
- Noisy neighbor effects

## Availability and Resilience

Cloud designs should consider:
- Regions
- Availability zones
- Redundancy
- Load balancing
- Auto scaling
- Backup and recovery

## Vendor Concerns

Important concerns include:
- Vendor lock-in
- Portability
- Interoperability
- Contractual obligations
- Exit strategy

## CCSP Exam Tips

- Location = where data is stored.
- Residency = where data must remain.
- Sovereignty = which laws apply.
- Portability = moving workloads/data.
- Interoperability = systems working together.

## Related Concepts

- Interoperability and Portability
- Cloud Deployment Models
- Shared Responsibility Model
- Domain 2 Data Security
