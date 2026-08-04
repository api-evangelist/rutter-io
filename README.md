# Rutter (rutter-io)

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

Rutter is a unified API for commerce, accounting, and payments. Developers integrate once and read and write normalized business data across QuickBooks, Xero, NetSuite, Sage Intacct, Shopify, Amazon, Stripe, and dozens of other platforms. Rutter authenticates with Basic auth (client_id:secret) and an X-Rutter-Version header, and scopes each request to an end-user's connection via an access_token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rutter-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rutter-io/refs/heads/main/apis.yml)

## Tags

- Unified API
- Accounting
- Commerce
- Payments
- Business Data
- Integrations

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Rutter Connections API

Manage the end-user connections that link a merchant's underlying platform (QuickBooks, Shopify, Stripe, etc.) to your app. Exchange a public token for a connection access_token, fetch connection metadata, and delete connections.

- **Human URL:** [https://docs.rutterapi.com/reference/get-connection](https://docs.rutterapi.com/reference/get-connection)
- **Base URL:** `https://production.rutterapi.com/versioned`

#### Tags

- Connections
- OAuth
- Link

#### Properties

- [Documentation](https://docs.rutterapi.com/docs/introduction)
- [API Reference](https://docs.rutterapi.com/reference/get-connection)
- [OpenAPI](openapi/rutter-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Accounting API

Normalized read and write access to accounting platforms - bank accounts, ledger accounts (chart of accounts), journal entries, invoices, bills, payments, expenses, and transactions across QuickBooks, Xero, NetSuite, and Sage Intacct.

- **Human URL:** [https://docs.rutterapi.com/reference/list-accounts](https://docs.rutterapi.com/reference/list-accounts)
- **Base URL:** `https://production.rutterapi.com/versioned/accounting`

#### Tags

- Accounting
- Ledger
- Journal Entries

#### Properties

- [Documentation](https://docs.rutterapi.com/docs/accounting)
- [API Reference](https://docs.rutterapi.com/reference/list-accounts)
- [OpenAPI](openapi/rutter-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Commerce API

Normalized read access to e-commerce and marketplace platforms - orders, products, customers, and transactions across Shopify, Amazon, WooCommerce, BigCommerce, and other storefronts and marketplaces.

- **Human URL:** [https://docs.rutterapi.com/reference/list-orders](https://docs.rutterapi.com/reference/list-orders)
- **Base URL:** `https://production.rutterapi.com/versioned/commerce`

#### Tags

- Commerce
- Orders
- Products

#### Properties

- [Documentation](https://docs.rutterapi.com/docs/commerce)
- [API Reference](https://docs.rutterapi.com/reference/list-orders)
- [OpenAPI](openapi/rutter-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Payments API

Normalized read access to payment processors - payments, payouts, balances, disputes, and transactions across Stripe, PayPal, Square, and other processors.

- **Human URL:** [https://docs.rutterapi.com/reference/list-payments](https://docs.rutterapi.com/reference/list-payments)
- **Base URL:** `https://production.rutterapi.com/versioned/payments`

#### Tags

- Payments
- Payouts
- Transactions

#### Properties

- [Documentation](https://docs.rutterapi.com/docs/payments)
- [API Reference](https://docs.rutterapi.com/reference/list-payments)
- [OpenAPI](openapi/rutter-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rutter Webhooks API

Register, list, and delete webhook endpoints and receive signed event notifications when a connection finishes its initial sync or when underlying data (orders, invoices, payments) is created or updated.

- **Human URL:** [https://docs.rutterapi.com/reference/list-webhooks](https://docs.rutterapi.com/reference/list-webhooks)
- **Base URL:** `https://production.rutterapi.com/versioned`

#### Tags

- Webhooks
- Events
- Sync

#### Properties

- [Documentation](https://docs.rutterapi.com/docs/webhooks)
- [API Reference](https://docs.rutterapi.com/reference/list-webhooks)
- [OpenAPI](openapi/rutter-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rutter-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rutter-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rutter-api)
- [Website](https://www.rutter.com)
- [Documentation](https://docs.rutterapi.com/docs/introduction)
- [Plans](plans/rutter-io-plans-pricing.yml)
- [Rate Limits](rate-limits/rutter-io-rate-limits.yml)
- [Fin Ops](finops/rutter-io-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
