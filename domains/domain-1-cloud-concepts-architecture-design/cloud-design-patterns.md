# Cloud Design Patterns

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🟡 Important
**Exam Frequency:** ⭐⭐⭐⭐

---

## Overview

Cloud design patterns are reusable solutions to common architectural and security challenges in cloud environments. Understanding these patterns helps design secure, resilient, and scalable systems.

---

## Availability Patterns

### High Availability (HA)
- Eliminates single points of failure
- Uses redundant components across availability zones or regions
- Target: minimize downtime (often measured as 99.9%, 99.99%, etc.)

### Fault Tolerance
- System continues operating despite component failure
- Goes beyond HA — no degradation in service

### Disaster Recovery (DR)
- Recovery after a major failure or outage
- Key metrics:
  - **RTO (Recovery Time Objective):** maximum acceptable downtime
  - **RPO (Recovery Point Objective):** maximum acceptable data loss

---

## Resilience Patterns

### Circuit Breaker
- Stops calls to a failing service to prevent cascading failures
- Returns an error immediately rather than waiting for timeout

### Retry with Backoff
- Retries failed operations with increasing delays
- Prevents overwhelming a struggling service

### Bulkhead
- Isolates components so failure in one doesn't affect others
- Analogous to ship bulkheads — contains failures

---

## Security Design Patterns

### Defense in Depth
- Multiple layers of security controls
- No single control is relied upon exclusively

### Secure by Default
- Systems start in a secure configuration
- Users must explicitly reduce security, not add it

### Least Privilege
- Minimum access rights required for tasks
- Applied to users, services, and processes

### Immutable Infrastructure
- Servers are never modified in place — replaced with new instances
- Reduces configuration drift and unauthorized changes

---

## Scalability Patterns

### Horizontal Scaling (Scale Out)
- Add more instances to handle load
- Preferred in cloud — aligns with elasticity

### Vertical Scaling (Scale Up)
- Increase resources on existing instance
- Limited by hardware maximums; less common in cloud

### Auto-scaling
- Automatically adjusts capacity based on demand
- Requires stateless application design

---

## Exam Tips

- RTO and RPO definitions are frequently tested
- Know the difference between HA and fault tolerance
- Defense in depth is a foundational CCSP principle
- Immutable infrastructure is a cloud-native security pattern
- Circuit breaker, bulkhead, and retry patterns appear in resilience questions

---

## Related Concepts

- [Cloud Computing Concepts](cloud-computing-concepts.md)
- [Interoperability and Portability](interoperability-portability.md)
- [Zero Trust Architecture](zero-trust-architecture.md)
