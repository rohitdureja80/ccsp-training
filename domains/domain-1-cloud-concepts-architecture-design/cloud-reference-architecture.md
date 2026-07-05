# Cloud Reference Architecture

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🟡 Important
**Exam Frequency:** ⭐⭐⭐⭐

---

## Overview

A cloud reference architecture provides a standardized framework describing cloud roles, activities, and relationships. The primary reference used in CCSP is the **CSA (Cloud Security Alliance) Enterprise Architecture** and the **NIST Cloud Computing Reference Architecture (NIST SP 500-292)**.

---

## NIST Cloud Computing Reference Architecture

### Five Major Actors

| Actor | Role |
|---|---|
| Cloud Consumer | Uses services provisioned by the provider |
| Cloud Provider | Delivers and manages the cloud service |
| Cloud Auditor | Independently assesses the service |
| Cloud Broker | Manages use, performance, and delivery of services |
| Cloud Carrier | Provides connectivity between consumer and provider |

---

## Cloud Provider Responsibilities

- **Service Layer:** SaaS, PaaS, IaaS delivery
- **Resource Abstraction & Control:** virtualization, orchestration
- **Physical Resource:** hardware, facilities

---

## CSA Security Architecture

### Key Components
- **Cloud Controls Matrix (CCM):** maps security controls to cloud domains
- **Consensus Assessments Initiative Questionnaire (CAIQ):** standardized security questionnaire for CSPs
- **Shared Security Model:** defines provider vs. customer obligations

### Architecture Layers
1. Infrastructure (compute, storage, network)
2. Metastructure (management plane, APIs)
3. Infostructure (data layer)
4. Applistructure (application layer)

---

## Metastructure

- The management plane of cloud infrastructure
- APIs and controls that configure and manage cloud resources
- High-value target: compromise of metastructure = full environment control
- Security focus: strong IAM, MFA, logging for all management plane access

---

## Exam Tips

- Know the five NIST actors and their roles
- CSA CCM and CAIQ are used for vendor assessment
- Metastructure is a key CCSP-specific concept — appears in multiple domains
- Cloud broker is distinct from cloud provider — adds value by aggregating services

---

## Related Concepts

- [Shared Responsibility Model](shared-responsibility-model.md)
- [Cloud Computing Concepts](cloud-computing-concepts.md)
- [Zero Trust Architecture](zero-trust-architecture.md)
