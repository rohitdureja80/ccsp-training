# Zero Trust Architecture

Priority: 🔴 Critical  
Exam Frequency: ⭐⭐⭐⭐⭐

## Definition

Zero Trust is a security model based on the principle:

> Never trust, always verify.

No user, device, application, or network is inherently trusted simply because it is inside the corporate network.

## Traditional vs Zero Trust

| Traditional Security | Zero Trust |
|---|---|
| Trust internal network | Trust no network by default |
| Network is perimeter | Identity is perimeter |
| Authenticate once | Continuously verify |
| Broad access after VPN | Least-privilege access per request |
| Flat internal networks | Micro-segmented resources |

## Why Cloud Supports Zero Trust Well

Cloud platforms are naturally aligned with Zero Trust because they are:

- Identity-centric
- API-driven
- Policy-based
- Highly logged
- Automation-friendly
- Designed for distributed access

## Key Zero Trust Signals

Access decisions may consider:

- User identity
- MFA status
- Device compliance
- Location
- Risk score
- Requested resource
- Session behavior

## Cloud Examples

### Azure

- Microsoft Entra ID
- Conditional Access
- Device compliance
- Named locations

### AWS

- IAM
- IAM Identity Center
- Organizations SCPs
- CloudTrail

### GCP

- Cloud IAM
- BeyondCorp-style access
- Context-Aware Access

## Exam Tip

If a question asks why Zero Trust is easier in cloud, the answer is usually because cloud uses centralized IAM, policy-based access, logging, and API-driven control.

