# Identity and Federation

**Domain:** 1 - Cloud Concepts, Architecture & Design
**Priority:** 🔴 Critical
**Exam Frequency:** ⭐⭐⭐⭐

---

## Identity in Cloud

Identity is the foundation of cloud security. Without a network perimeter, identity becomes the primary control plane.

Cloud identity management involves:
- Authentication: verifying who a user or service is
- Authorization: determining what they can do
- Accountability: logging and auditing actions

---

## Key Identity Concepts

### Identity Provider (IdP)
- The authoritative source for user identity
- Issues tokens/assertions used for authentication
- Examples: Azure AD, Okta, Google Identity

### Service Provider (SP)
- The application or service relying on the IdP for authentication
- Trusts the IdP's assertions

### Federated Identity
- Allows a single identity to be used across multiple systems or organizations
- Eliminates the need for separate accounts per system
- Based on trust relationships between IdPs and SPs

---

## Federation Protocols

### SAML (Security Assertion Markup Language)
- XML-based standard for exchanging authentication/authorization data
- Common in enterprise SSO scenarios
- Assertion types: Authentication, Attribute, Authorization Decision

### OAuth 2.0
- Authorization framework (not authentication)
- Allows third-party apps to access resources on behalf of a user
- Uses access tokens

### OpenID Connect (OIDC)
- Authentication layer built on top of OAuth 2.0
- Adds identity (ID token) to OAuth's authorization
- Widely used in modern cloud and mobile apps

---

## Single Sign-On (SSO)

- One login grants access to multiple systems
- Reduces password fatigue and improves user experience
- Increases risk if the SSO credential is compromised (single point of failure)
- Mitigated with MFA

---

## Multi-Factor Authentication (MFA)

- Something you know (password)
- Something you have (token, phone)
- Something you are (biometrics)
- Required for privileged access in cloud environments

---

## Privileged Identity Management (PIM)

- Just-in-time access for privileged roles
- Time-limited and approval-gated elevation
- Reduces standing privileged access

---

## Exam Tips

- Know SAML vs OAuth vs OIDC — their purpose and use cases
- Federation enables cross-domain trust — know IdP and SP roles
- SSO is convenient but creates a high-value target — always pair with MFA
- CCSP heavily tests identity in the context of cloud access and Zero Trust
- OAuth is authorization, OIDC adds authentication on top

---

## Related Concepts

- [Zero Trust Architecture](zero-trust-architecture.md)
- [Shared Responsibility Model](shared-responsibility-model.md)
- [Cloud Reference Architecture](cloud-reference-architecture.md)
