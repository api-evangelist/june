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
