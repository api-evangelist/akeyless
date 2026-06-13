# Akeyless (akeyless)

Akeyless is a cloud-native identity security platform that unifies secrets management, machine identity, and privileged access for AI agents, machines, and humans at scale. Built on patented Distributed Fragments Cryptography (DFC) technology, Akeyless delivers zero-knowledge, quantum-safe security without requiring central key storage. The platform provides a REST API with 200+ endpoints covering secrets vaulting, dynamic secrets generation, certificate lifecycle management, encryption and multi-cloud KMS, and SSH access governance. The API supports multiple authentication methods including AWS IAM, Azure AD, GCP, Kubernetes, SAML, OIDC, LDAP, and API key authentication.

- **APIs.json**: https://raw.githubusercontent.com/api-evangelist/akeyless/refs/heads/main/apis.yml
- **Naftiko**: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=akeyless-api-evangelist&utm_content=repo

## Tags

- Secrets Management
- Zero Trust
- Cloud Security
- Identity Security
- Machine Identity
- Certificate Management
- PKI
- KMS
- Encryption
- SSH Access
- Dynamic Secrets
- Privileged Access Management
- DevSecOps

## APIs

### Akeyless REST API

The Akeyless V2 REST API provides programmatic access to all platform capabilities including secrets management, dynamic secrets, encryption operations, certificate lifecycle management, and SSH access control. The API is accessible at the global SaaS endpoint (`https://api.akeyless.io`) or via self-hosted gateway deployments on port 8081 or 8080/v2.

- **Documentation**: https://docs.akeyless.io/
- **Base URL**: https://api.akeyless.io

#### SDKs

| Language | Repository |
|----------|-----------|
| Go | https://github.com/akeylesslabs/akeyless-go |
| Python | https://github.com/akeylesslabs/akeyless-python |
| Java | https://github.com/akeylesslabs/akeyless-java |
| Ruby | https://github.com/akeylesslabs/akeyless-ruby |
| JavaScript/Node.js | https://www.npmjs.com/package/akeyless |

## Plans / Rate Limits / FinOps

| Resource | Path |
|----------|------|
| Plans & Pricing | [plans/akeyless-plans-pricing.yml](plans/akeyless-plans-pricing.yml) |
| Rate Limits | [rate-limits/akeyless-rate-limits.yml](rate-limits/akeyless-rate-limits.yml) |
| FinOps | [finops/akeyless-finops.yml](finops/akeyless-finops.yml) |

**Pricing model**: Usage-based, measured by active clients, secret connectors, managed certificates, KMS transactions, KMIP/TDE applications, tokenizer instances, and cloud accounts. Free tier available; Enterprise pricing is custom.

**Rate limits**: The Free tier caps KMS transactions at 1,000/day and 5 active clients/month. Enterprise limits are custom negotiated volumes.

## Timestamps

- **Created**: 2026-06-13
- **Modified**: 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://www.akeyless.io/ |
| Documentation | https://docs.akeyless.io/ |
| GitHub Org | https://github.com/akeylesslabs |
| LinkedIn | https://www.linkedin.com/company/akeyless |
| Blog | https://www.akeyless.io/blog/ |
| Pricing | https://www.akeyless.io/pricing/ |
| Status Page | https://status.akeyless.io/ |
| X / Twitter | https://x.com/akeylessio |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
