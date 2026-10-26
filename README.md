# Dynamic (dynamic-labs)

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
