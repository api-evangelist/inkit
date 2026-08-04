# Inkit (inkit)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Inkit is a Secure Document Generation (SDG) platform that enables organizations to generate, sign, store, and distribute documents in total privacy. The platform provides a REST API for rendering HTML templates into PDFs, automating document workflows, and managing digital signatures at scale. Inkit supports enterprise-grade security and compliance including HIPAA, SOC 2, FedRAMP, and IL4/IL5 certifications, making it suitable for regulated industries such as financial services, utilities, and government.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/inkit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/inkit/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=inkit-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=inkit-api-evangelist&utm_content=repo)

## Tags

- Document Generation
- PDF
- Templates
- Digital Signatures
- Workflows
- Document Management
- Secure Documents
- Compliance
- HIPAA
- Enterprise

## APIs

### Inkit Document Generation API

The Inkit REST API enables developers to generate PDF documents from templates, manage document storage and retrieval, launch document workflows and batches, send documents via mail, and manage digital signature requests. Authentication uses the `X-Inkit-API-Token` header and the API enforces a rate limit of 300 requests per minute.

- **Human URL:** [https://docs.inkit.com/docs/using-the-api](https://docs.inkit.com/docs/using-the-api)
- **Base URL:** `https://api.inkit.com/v1`
- **API Reference:** [https://docs.inkit.com/reference/post_v1-generate-1](https://docs.inkit.com/reference/post_v1-generate-1)

## Plans / Rate Limits / FinOps

- **Plans & Pricing:** [plans/inkit-plans-pricing.yml](plans/inkit-plans-pricing.yml)
- **Rate Limits:** [rate-limits/inkit-rate-limits.yml](rate-limits/inkit-rate-limits.yml)
- **FinOps:** [finops/inkit-finops.yml](finops/inkit-finops.yml)

Inkit offers four plan tiers: Free ($0), Personal ($15/user/month annual), Standard ($25/user/month annual), and Enterprise (custom pricing). API access is available exclusively on the Enterprise plan, with usage-based billing for API automations and workflow invocations. The API enforces a rate limit of 300 requests per minute per account.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.inkit.com](https://www.inkit.com) |
| Documentation | [https://docs.inkit.com/docs/welcome-to-inkit](https://docs.inkit.com/docs/welcome-to-inkit) |
| GitHub Organization | [https://github.com/inkit](https://github.com/inkit) |
| LinkedIn | [https://www.linkedin.com/company/inkit](https://www.linkedin.com/company/inkit) |
| X | [https://x.com/inkittweet](https://x.com/inkittweet) |
| Blog | [https://www.inkit.com/blog](https://www.inkit.com/blog) |
| Pricing | [https://www.inkit.com/pricing](https://www.inkit.com/pricing) |
| Status Page | [https://status.inkit.com/](https://status.inkit.com/) |

## Maintainers

- **Kin Lane** - [kin@apievangelist.com](mailto:kin@apievangelist.com)
