# Cloud Security Principles

**Domain:** 1 - Cloud Concepts, Architecture & Design  
**Priority:** 🔴 Critical  
**Exam Frequency:** ⭐⭐⭐⭐⭐

## Overview

Cloud security architecture should be based on core security principles that apply across all service and deployment models.

## Key Principles

### Defense in Depth

Use multiple layers of controls so that failure of one control does not result in total compromise.

Examples:
- MFA
- IAM least privilege
- Network segmentation
- Encryption
- Logging and monitoring

### Least Privilege

Grant only the permissions required to perform a task.

CCSP clue: excessive permissions, overprivileged roles, or broad admin rights.

### Separation of Duties

Split sensitive responsibilities across multiple people or roles to reduce fraud, abuse, and accidental misuse.

### Secure by Default

Systems should start from a secure configuration rather than requiring users to manually harden everything.

### Fail Secure

If a system fails, it should fail into a safe state rather than an open or permissive state.

### Complete Mediation

Every access request should be checked, not just the first one.

This connects strongly to Zero Trust.

### Economy of Mechanism

Security mechanisms should be as simple as possible to reduce implementation errors.

## CCSP Exam Tips

- Least privilege is usually the best answer when the issue involves excessive access.
- Defense in depth is usually the best answer when the question asks for layered protection.
- Separation of duties is usually the best answer when the question involves preventing abuse by a single individual.

## Related Concepts

- Zero Trust Architecture
- IAM
- Shared Responsibility Model
- Governance
