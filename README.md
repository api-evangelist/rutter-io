# Rutter (rutter-io)

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
