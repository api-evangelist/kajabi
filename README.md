# Kajabi (kajabi)

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
