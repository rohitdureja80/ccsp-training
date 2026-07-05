# Domain 1 - High-Yield Review

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Purpose:** Fast review of the most exam-relevant concepts before test day

---

## Critical Concepts (🔴)

### NIST Five Characteristics of Cloud
1. On-demand self-service
2. Broad network access
3. Resource pooling
4. Rapid elasticity
5. Measured service

### Service Models — Who Owns What
| Layer | IaaS | PaaS | SaaS |
|---|---|---|---|
| Data | Customer | Customer | Customer |
| Application | Customer | Customer | Provider |
| OS | Customer | Provider | Provider |
| Hardware | Provider | Provider | Provider |

### Shared Responsibility
- Provider: security *of* the cloud (infrastructure, physical)
- Customer: security *in* the cloud (data, identity, config)
- Data ownership and classification ALWAYS stay with the customer

### Zero Trust — Core Principles
- Never trust, always verify
- Least privilege access
- Microsegmentation
- Assume breach
- NIST ZTA components: Policy Engine, Policy Administrator, Policy Enforcement Point

### Identity and Federation
- SAML: enterprise SSO, XML-based
- OAuth 2.0: authorization (not authentication)
- OIDC: authentication on top of OAuth
- SSO risk: single point of failure — mitigate with MFA

---

## Important Concepts (🟡)

### Deployment Models
| Model | Tenancy | Key Trait |
|---|---|---|
| Public | Multi-tenant | Lowest cost, least control |
| Private | Single-tenant | Most control, highest cost |
| Community | Shared (select orgs) | Shared governance |
| Hybrid | Mixed | Flexibility, complexity |

### NIST Cloud Actors
- Consumer, Provider, Auditor, Broker, Carrier

### Metastructure
- Management plane / API layer
- High-value attack target
- Secure with IAM, MFA, full audit logging

### Portability vs. Interoperability
- Portability: ability to move workloads/data
- Interoperability: ability to work across systems
- Vendor lock-in mitigation: open standards, containers, IaC, contractual exit rights

### Key DR Metrics
- **RTO:** how fast to recover (downtime tolerance)
- **RPO:** how much data loss is acceptable

### Resilience Patterns
- Circuit Breaker, Bulkhead, Retry with Backoff
- Defense in Depth, Least Privilege, Immutable Infrastructure

---

## Common Exam Traps

- SaaS doesn't remove customer responsibility for data
- Community cloud is NOT public cloud
- OAuth is authorization only — OIDC adds identity
- Elasticity is automatic; scalability may be manual
- Vendor lock-in is a business and security risk
- Metastructure compromise = full environment compromise

---

## Quick Reference Links

- [Cloud Computing Concepts](cloud-computing-concepts.md)
- [Cloud Service Models](cloud-service-models.md)
- [Cloud Deployment Models](cloud-deployment-models.md)
- [Shared Responsibility Model](shared-responsibility-model.md)
- [Cloud Reference Architecture](cloud-reference-architecture.md)
- [Zero Trust Architecture](zero-trust-architecture.md)
- [Identity and Federation](identity-and-federation.md)
- [Cloud Design Patterns](cloud-design-patterns.md)
- [Interoperability and Portability](interoperability-portability.md)
