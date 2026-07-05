# Zero Trust Architecture

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🔴 Critical
**Exam Frequency:** ⭐⭐⭐⭐⭐

---

## Core Principle

"Never trust, always verify."

Zero Trust assumes no user, device, or network segment is inherently trusted — even if inside the corporate perimeter. Every access request must be authenticated, authorized, and continuously validated.

---

## Why Zero Trust in Cloud

Traditional perimeter-based security assumes trust inside the network. Cloud environments eliminate the traditional perimeter:
- Users access resources from anywhere
- Workloads span multiple providers and regions
- Lateral movement within a trusted network is a major threat vector

---

## Zero Trust Pillars

| Pillar | Description |
|---|---|
| Identity | Verify every user and service identity explicitly |
| Device | Assess device health and compliance before granting access |
| Network | Microsegmentation, encrypt all traffic, assume breach |
| Application | Least-privilege access per application, per session |
| Data | Classify and protect data regardless of location |

---

## Key Concepts

### Least Privilege
- Grant only the minimum access needed for a specific task
- Apply to users, services, and applications

### Microsegmentation
- Divide the network into small zones
- Limit lateral movement if a segment is compromised

### Continuous Verification
- Authentication is not a one-time event
- Re-evaluate trust based on context (location, behavior, device state)

### Assume Breach
- Design systems as if the attacker is already inside
- Focus on detection, isolation, and recovery

---

## NIST SP 800-207

NIST's Zero Trust Architecture publication defines:
- Logical components: Policy Engine, Policy Administrator, Policy Enforcement Point
- Deployment models: identity-centric, network-centric, device-agent-based

---

## Exam Tips

- Zero Trust is identity-centric, not perimeter-centric
- Know the three NIST ZTA components: Policy Engine, Policy Administrator, Policy Enforcement Point
- Microsegmentation and least privilege are core ZTA controls
- ZTA does not eliminate perimeter controls — it supplements them
- ZTA is highly relevant to cloud because there is no traditional perimeter

---

## Related Concepts

- [Identity and Federation](identity-and-federation.md)
- [Cloud Design Patterns](cloud-design-patterns.md)
- [Shared Responsibility Model](shared-responsibility-model.md)
