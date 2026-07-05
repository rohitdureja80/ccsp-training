# Cloud Computing Concepts

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🔴 Critical
**Exam Frequency:** ⭐⭐⭐⭐⭐

---

## NIST Definition of Cloud Computing

Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources that can be rapidly provisioned and released with minimal management effort or service provider interaction.

---

## Five Essential Characteristics

| Characteristic | Description |
|---|---|
| On-demand self-service | Users provision resources without human interaction |
| Broad network access | Available over the network via standard mechanisms |
| Resource pooling | Multi-tenant model, location independence |
| Rapid elasticity | Capabilities scale up/down automatically |
| Measured service | Resource usage monitored, controlled, and reported |

---

## Key Concepts

### Multi-tenancy
- Multiple customers share the same physical infrastructure
- Logical isolation required between tenants
- Security risk: data leakage across tenant boundaries

### Elasticity vs. Scalability
- **Elasticity:** automatic, dynamic scaling in response to demand
- **Scalability:** ability to handle increased load (may be manual)

### Virtualization
- Abstracts physical hardware into logical resources
- Enables multi-tenancy and resource pooling
- Types: server, storage, network, desktop

---

## Exam Tips

- NIST SP 800-145 is the authoritative definition of cloud computing
- Know all five essential characteristics — they appear frequently
- Multi-tenancy is a core cloud risk; isolation is the key control
- Elasticity is automatic; scalability may not be

---

## Related Concepts

- [Cloud Service Models](cloud-service-models.md)
- [Cloud Deployment Models](cloud-deployment-models.md)
- [Shared Responsibility Model](shared-responsibility-model.md)
