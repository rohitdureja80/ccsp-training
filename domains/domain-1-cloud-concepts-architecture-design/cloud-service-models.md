# Cloud Service Models

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🔴 Critical
**Exam Frequency:** ⭐⭐⭐⭐⭐

---

## The Three Service Models

### IaaS - Infrastructure as a Service
- Provider manages: physical hardware, networking, hypervisor
- Customer manages: OS, middleware, runtime, data, applications
- Examples: AWS EC2, Azure VMs, Google Compute Engine
- Security responsibility: highest for customer

### PaaS - Platform as a Service
- Provider manages: infrastructure + OS + runtime + middleware
- Customer manages: applications and data
- Examples: AWS Elastic Beanstalk, Azure App Service, Google App Engine
- Security responsibility: shared, customer focuses on app-level

### SaaS - Software as a Service
- Provider manages: everything including the application
- Customer manages: data configuration and user access
- Examples: Microsoft 365, Salesforce, Google Workspace
- Security responsibility: least for customer, most for provider

---

## Responsibility Comparison

| Layer | IaaS | PaaS | SaaS |
|---|---|---|---|
| Application | Customer | Customer | Provider |
| Data | Customer | Customer | Customer* |
| Runtime | Customer | Provider | Provider |
| OS | Customer | Provider | Provider |
| Virtualization | Provider | Provider | Provider |
| Hardware | Provider | Provider | Provider |

*Data governance and classification remain the customer's responsibility in all models.

---

## Security Implications by Model

- **IaaS:** Most flexibility, most attack surface for customer to manage
- **PaaS:** Reduced OS/runtime risk, but app-level vulnerabilities remain customer-owned
- **SaaS:** Least control, reliance on provider security; focus on access management and data handling

---

## Exam Tips

- Know which layers each party owns in each model
- Data classification and ownership always remain with the customer
- SaaS doesn't mean zero customer responsibility
- Misconfigurations in SaaS (e.g., permissions, sharing settings) are customer-side risks

---

## Related Concepts

- [Cloud Computing Concepts](cloud-computing-concepts.md)
- [Shared Responsibility Model](shared-responsibility-model.md)
- [Cloud Deployment Models](cloud-deployment-models.md)
