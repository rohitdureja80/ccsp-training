# Cloud Design Patterns

Priority: 🟡 Important  
Exam Frequency: ⭐⭐⭐⭐

## Overview

Cloud design patterns are reusable architecture solutions for common cloud problems such as resilience, scalability, reliability, and fault isolation.

## High-Yield Patterns

| Pattern | Purpose |
|---|---|
| Retry | Handles transient failures |
| Circuit Breaker | Stops calls to unhealthy services |
| Bulkhead | Isolates failures between components |
| Queue-Based Load Leveling | Smooths spikes in demand |
| Cache-Aside | Improves performance and reduces backend load |
| Active-Active | Multiple systems actively serve traffic |
| Active-Passive | Standby system takes over during failure |

## Retry Pattern

Used when temporary failures are expected, such as brief network or service interruptions.

## Circuit Breaker Pattern

Prevents repeated calls to a failing dependency and allows the system to degrade gracefully.

## Bulkhead Pattern

Limits blast radius by isolating components, similar to watertight compartments on a ship.

## Queue-Based Load Leveling

Uses a queue between producers and consumers to absorb traffic spikes and maintain availability.

## CCSP Exam Tip

If a question asks about resilience, availability, or fault isolation, cloud design patterns may be the underlying concept.

