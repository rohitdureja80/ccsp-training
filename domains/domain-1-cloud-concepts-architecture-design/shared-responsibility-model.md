# Shared Responsibility Model

Priority: 🔴 Critical  
Exam Frequency: ⭐⭐⭐⭐⭐

## Definition

The Shared Responsibility Model defines which security responsibilities belong to the cloud provider and which belong to the cloud customer.

The cloud provider is generally responsible for **security of the cloud**.

The customer is generally responsible for **security in the cloud**.

## Key Principle

The more managed the cloud service, the more responsibility shifts to the provider.

| Layer | IaaS | PaaS | SaaS |
|---|---|---|---|
| Data | Customer | Customer | Customer |
| Application | Customer | Customer | Shared/CSP |
| Runtime | Customer | CSP | CSP |
| Middleware | Customer | CSP | CSP |
| Operating System | Customer | CSP | CSP |
| Virtualization | CSP | CSP | CSP |
| Physical Infrastructure | CSP | CSP | CSP |

## Common Exam Trap

The CSP does not automatically secure everything. Customers remain responsible for:

- Data
- Identity and access management
- Configuration
- Classification
- Legal and regulatory obligations
- Application security, depending on service model

## Example

In IaaS, the provider secures the hypervisor and physical host, but the customer patches the guest OS.

In PaaS, the provider patches the OS and runtime, but the customer secures the application and data.

## Exam Tip

If a question asks who is responsible, first identify the service model.

