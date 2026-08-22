# Kajabi (kajabi)

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

Kajabi is an all-in-one creator platform that enables entrepreneurs and knowledge creators to build, market, and sell digital products including online courses, membership sites, coaching programs, and communities. The Kajabi Public API provides a RESTful interface for managing contacts, products, offers, purchases, orders, transactions, forms, websites, webhooks, and Kajabi Payments payouts. API access is available exclusively on the Pro plan and uses OAuth 2.0 for authentication. The base URL is `https://api.kajabi.com` with endpoints versioned under `/v1`, and an OpenAPI specification is published in Kajabi's public GitHub repository.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/kajabi/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=kajabi-api-evangelist&utm_content=repo

---

## Tags

- Creator Economy
- Online Courses
- Memberships
- E-Commerce
- Digital Products
- Contacts
- Webhooks
- Payments

---

## APIs

### Kajabi Public API

RESTful API for managing contacts, products, offers, purchases, orders, transactions, courses, forms, landing pages, websites, webhooks, and Kajabi Payments payouts.

- **Documentation:** https://help.kajabi.com/api-reference/introduction
- **Base URL:** https://api.kajabi.com
- **OpenAPI Spec:** https://github.com/Kajabi/public_api_docs/blob/main/openapi.yaml

**Resources available via API:**

| Resource | Operations |
|---|---|
| Authentication | Get access token, Revoke token |
| Contacts | List, Create, Get, Update, Delete, Tags, Offers |
| Contact Notes | List, Create, Get, Update, Delete |
| Contact Tags | List, Get |
| Courses | List, Get |
| Custom Fields | List, Get |
| Customers | List, Get, Offers |
| Forms | List, Get, Submit, Submissions |
| Landing Pages | List, Get |
| Offers | List, Get, Products |
| Orders | List, Get, Items |
| Products | List, Get |
| Purchases | List, Get, Cancel, Deactivate, Reactivate |
| Sites / Pages | List, Get |
| Transactions | List, Get |
| Webhooks | List, Create, Get, Delete |
| Payments Payouts | List, Get |

---

## Plans / Rate Limits / FinOps

| File | Description |
|---|---|
| [plans/kajabi-plans-pricing.yml](plans/kajabi-plans-pricing.yml) | Subscription tiers — Kickstarter, Basic, Growth, Pro |
| [rate-limits/kajabi-rate-limits.yml](rate-limits/kajabi-rate-limits.yml) | API rate limit policies and response headers |
| [finops/kajabi-finops.yml](finops/kajabi-finops.yml) | FOCUS-aligned cost model including subscription, transaction, and contact fees |

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common Properties

| Type | URL |
|---|---|
| Website | https://www.kajabi.com |
| Documentation | https://help.kajabi.com/api-reference/introduction |
| GitHub Organization | https://github.com/Kajabi |
| LinkedIn | https://www.linkedin.com/company/kajabi |
| Blog | https://www.kajabi.com/blog |
| Pricing | https://www.kajabi.com/pricing |
| Status Page | https://status.kajabi.com |
| X (Twitter) | https://x.com/Kajabi |

---

## Maintainers

- **Kin Lane** — kin@apievangelist.com
