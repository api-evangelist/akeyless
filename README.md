# Akeyless (akeyless)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
