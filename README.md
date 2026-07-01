# Dynamic (dynamic-labs)

Dynamic is a web3 authentication and embedded wallet platform. It provides multi-chain login, embedded and smart wallets secured with MPC-TSS, onramps, and end-to-end user management through a developer dashboard, client SDKs, and an environment-scoped REST API for programmatically managing users, wallets, projects, webhooks, and token verification.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dynamic-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dynamic-labs/refs/heads/main/apis.yml)

## Tags

- Web3
- Authentication
- Embedded Wallets
- Wallets
- MPC
- Onboarding
- Crypto

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Dynamic Users API

List, retrieve, update, export, and delete end users authenticated into a Dynamic environment, along with their linked verified credentials and OAuth accounts.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/users](https://www.dynamic.xyz/docs/api-reference/users)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Users
- Management
- Identity

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/users)
- [API Reference](https://www.dynamic.xyz/docs/api-reference/users)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Wallets API

View and manage the wallets linked to users in an environment across supported EVM, Solana, Bitcoin, and other chains.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/wallets](https://www.dynamic.xyz/docs/api-reference/wallets)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Wallets
- Multi-Chain
- Crypto

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/wallets)
- [API Reference](https://www.dynamic.xyz/docs/api-reference/wallets/get-wallets-by-user)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Embedded Wallets API

Programmatically create MPC-TSS embedded wallets for users, generating self-custodial keys split across parties without seed phrases.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/embedded-wallets](https://www.dynamic.xyz/docs/api-reference/embedded-wallets)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Embedded Wallets
- MPC
- TSS

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/embedded-wallets)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Environments API

Retrieve and update environment (project) configuration and settings, and programmatically provision isolated sandbox and live environments.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/environments](https://www.dynamic.xyz/docs/api-reference/environments)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Environments
- Projects
- Settings

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/environments)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic API Tokens API

Create, list, and revoke environment-scoped API tokens (dyn_ prefixed bearer tokens) used to authenticate admin API requests.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/tokens](https://www.dynamic.xyz/docs/api-reference/tokens)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- API Tokens
- Access
- Security

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/tokens/create-a-new-api-token)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Webhooks API

Register, list, update, and delete webhook endpoints that receive signed event notifications for user, wallet, and session lifecycle events.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/webhooks](https://www.dynamic.xyz/docs/api-reference/webhooks)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/webhooks)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Token Verification API

Fetch the environment JSON Web Key Set (JWKS) used to verify Dynamic JWT auth tokens server-side, plus SDK utility endpoints such as URL threat scanning.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/sdk/find-jwks-for-public-key-json-format](https://www.dynamic.xyz/docs/api-reference/sdk/find-jwks-for-public-key-json-format)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- JWKS
- Token Verification
- SDK

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/sdk/find-jwks-for-public-key-json-format)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Allowlists API

Create and manage allowlists and allowlist entries to gate who can authenticate into an environment by email, wallet address, or other criteria.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/allowlists](https://www.dynamic.xyz/docs/api-reference/allowlists)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Allowlists
- Access Control
- Gating

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/allowlists)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Analytics API

Retrieve aggregate analytics for an environment, including user, wallet, and transaction metrics for reporting and dashboards.

- **Human URL:** [https://www.dynamic.xyz/docs/api-reference/analytics](https://www.dynamic.xyz/docs/api-reference/analytics)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Analytics
- Metrics
- Reporting

#### Properties

- [Documentation](https://www.dynamic.xyz/docs/api-reference/analytics/get-environments-analyticswallets)
- [OpenAPI](openapi/dynamic-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dynamic-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dynamic-labs)
- [LinkedIn](https://www.linkedin.com/company/dynamic-labs-financial)
- [Website](https://www.dynamic.xyz)
- [Documentation](https://docs.dynamic.xyz)
- [Plans](plans/dynamic-labs-plans-pricing.yml)
- [Rate Limits](rate-limits/dynamic-labs-rate-limits.yml)
- [Fin Ops](finops/dynamic-labs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
