# Shared Responsibility Model

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🔴 Critical
**Exam Frequency:** ⭐⭐⭐⭐⭐

---

## Core Concept

The shared responsibility model defines the division of security obligations between the cloud service provider (CSP) and the cloud customer. The boundary shifts depending on the service model used.

**Key principle:** The CSP is responsible for security *of* the cloud; the customer is responsible for security *in* the cloud.

---

## Responsibility by Service Model

| Security Area | IaaS | PaaS | SaaS |
|---|---|---|---|
| Data classification & accountability | Customer | Customer | Customer |
| Identity & access management | Customer | Customer | Shared |
| Application-level controls | Customer | Customer | Provider |
| OS patching | Customer | Provider | Provider |
| Network controls | Shared | Provider | Provider |
| Physical security | Provider | Provider | Provider |

---

## What Always Stays with the Customer

Regardless of service model:
- Data ownership and classification
- User identity and access management
- Compliance and legal obligations
- Configuration of cloud services
- Incident response planning

---

## Common Misunderstandings

- Moving to SaaS does not transfer data privacy liability
- The provider securing infrastructure does not mean applications are secure
- Misconfigurations (e.g., open S3 buckets) are customer failures, not provider failures
- Shared responsibility does not mean equal responsibility

---

## Exam Tips

- This is one of the most tested concepts in the CCSP exam
- Know the model for IaaS, PaaS, and SaaS separately
- Data and identity always remain the customer's concern
- Exam scenarios often test whether a security gap is the provider's or customer's fault

---

## Related Concepts

- [Cloud Service Models](cloud-service-models.md)
- [Cloud Reference Architecture](cloud-reference-architecture.md)
- [Identity and Federation](identity-and-federation.md)
