# June (june)

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

June is a product analytics platform purpose-built for B2B SaaS companies, providing company-level and user-level analytics focused on key SaaS metrics such as activation, retention, and feature adoption. The platform offers a REST-based Tracking API compatible with the Segment protocol, enabling teams to identify users, track events, group users into companies, and record page views. June also provides server-side SDKs for Node.js, Python, and Ruby, as well as client-side JavaScript and React/Next.js libraries. An Embed API (available as a Pro Plan add-on) allows embedding June dashboards directly into customer-facing products, and a Data Deletions API supports GDPR compliance by enabling deletion of user and workspace data.

The APIs.json index for this provider is available at: https://raw.githubusercontent.com/api-evangelist/june/refs/heads/main/apis.yml

Explore and manage June APIs with the Naftiko fleet: [Naftiko Fleet](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=june-api-evangelist&utm_content=repo)

## Tags

- Analytics
- Product Analytics
- B2B SaaS
- Event Tracking
- Segment Compatible
- Retention
- Feature Adoption
- Activation

## APIs

| API | Description |
|-----|-------------|
| [June Tracking API](https://www.june.so/docs/tracking/http-api/authentication) | REST API for sending user behaviour data including identify, track, group, and page calls. Base URL: `https://api.june.so/sdk/`. Basic Auth with write key. |
| [June Embed API](https://help.june.so/en/articles/9832226-api-documentation) | Pro Plan add-on for embedding June analytics dashboards in customer-facing products. |
| [June Data Deletions API](https://help.june.so/en/articles/9832226-api-documentation) | API for deleting users and workspace data to support GDPR/privacy compliance. |

## Plans / Rate Limits / FinOps

| Resource | Description |
|----------|-------------|
| [Plans & Pricing](plans/june-plans-pricing.yml) | MAU-based subscription pricing; all features included; Embed API as add-on; custom quotes via sales. |
| [Rate Limits](rate-limits/june-rate-limits.yml) | Rate limits not publicly disclosed; HTTP 429 used for throttling; Basic Auth via write key. |
| [FinOps](finops/june-finops.yml) | MAU-metered billing model; FOCUS-aligned columns; Visibility and Optimization principles. |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.june.so/ |
| Documentation | https://www.june.so/docs |
| GitHub Organization | https://github.com/juneHQ |
| LinkedIn | https://www.linkedin.com/company/juneso |
| X / Twitter | https://x.com/juneDotSo |
| Blog | https://www.june.so/blog |
| Changelog | https://changelog.june.so |
| Pricing | https://www.june.so/pricing |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
