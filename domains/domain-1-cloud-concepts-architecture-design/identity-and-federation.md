# Identity and Federation

Priority: 🔴 Critical  
Exam Frequency: ⭐⭐⭐⭐

## Definition

Federation allows an organization to use an existing identity provider to authenticate users into another system, such as a cloud provider tenant.

## Simple Explanation

To federate a customer's IAM system with a CSP tenant means:

> The customer keeps its existing identity system, and the CSP trusts it for authentication.

## Example

A company uses Microsoft Entra ID or an on-premises identity provider. Users sign in with corporate credentials and access Azure, AWS, or SaaS applications without separate local cloud accounts.

## Benefits

- Centralized identity management
- Single sign-on
- Reduced password sprawl
- Easier offboarding
- Consistent MFA and conditional access policies

## Related Standards and Protocols

- SAML
- OAuth
- OpenID Connect
- WS-Federation

## Exam Tip

Federation is about trust between identity providers and service providers. It does not eliminate the need for authorization, least privilege, or monitoring.

## Related Concepts

- Zero Trust
- Identity assurance
- Conditional access
- MFA
- Shared Responsibility Model

