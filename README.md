# Alpaca (alpaca)

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

Alpaca is an API-first commission-free stock and crypto trading broker offering trading, market data, options, and broker-as-a-service APIs. Alpaca publishes its OpenAPI specifications publicly via the alpacahq/alpaca-docs GitHub repository, with separate specs for Trading, Broker, Market Data, and OAuth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alpaca/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alpaca/refs/heads/main/apis.yml)

## Tags

- Fintech
- Trading
- Stocks
- Crypto
- Brokerage
- Market Data
- Options

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Alpaca Trading API

The Alpaca Trading API enables commission-free trading of US-listed equities, options, and crypto. It exposes endpoints for orders, positions, account information, watchlists, calendar, clock, and assets. A paper trading sandbox is available at paper-api.alpaca.markets.

- **Human URL:** [https://docs.alpaca.markets/docs/trading-api](https://docs.alpaca.markets/docs/trading-api)
- **Base URL:** `https://api.alpaca.markets/v2`

#### Tags

- Trading
- Stocks
- Options
- Crypto
- Orders

#### Properties

- [Documentation](https://docs.alpaca.markets/docs/trading-api)
- [OpenAPI](openapi/alpaca-trading-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alpaca-trading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alpaca-trading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/alpaca-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Sandbox](https://paper-api.alpaca.markets/v2)

### Alpaca Market Data API

The Alpaca Market Data API delivers real-time and historical pricing data for US stocks (SIP and IEX feeds), options (OPRA), and crypto. Supports REST and WebSocket streaming with bars, quotes, trades, snapshots, and corporate actions endpoints. 7+ years of historical data available.

- **Human URL:** [https://docs.alpaca.markets/docs/about-market-data-api](https://docs.alpaca.markets/docs/about-market-data-api)
- **Base URL:** `https://data.alpaca.markets`

#### Tags

- Market Data
- Stocks
- Crypto
- Options
- Real-time
- Historical

#### Properties

- [Documentation](https://docs.alpaca.markets/docs/about-market-data-api)
- [OpenAPI](openapi/alpaca-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alpaca-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alpaca-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/alpaca-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Alpaca Broker API

The Alpaca Broker API powers white-label brokerage and embedded finance products. It exposes endpoints for account onboarding, KYC/AML, ACATS transfers, ACH funding, journals, and trading on behalf of end users.

- **Human URL:** [https://docs.alpaca.markets/docs/about-broker-api](https://docs.alpaca.markets/docs/about-broker-api)
- **Base URL:** `https://broker-api.alpaca.markets/v1`

#### Tags

- Brokerage
- Embedded Finance
- White Label
- Compliance
- Trading

#### Properties

- [Documentation](https://docs.alpaca.markets/docs/about-broker-api)
- [OpenAPI](openapi/alpaca-broker-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alpaca-broker-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alpaca-broker-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Alpaca OAuth API

The Alpaca OAuth API allows third-party applications to authenticate Alpaca users and obtain access tokens for the Trading and Market Data APIs.

- **Human URL:** [https://docs.alpaca.markets/docs/oauth-tokens](https://docs.alpaca.markets/docs/oauth-tokens)
- **Base URL:** `https://api.alpaca.markets/oauth`

#### Tags

- OAuth
- Authentication
- Authorization

#### Properties

- [Documentation](https://docs.alpaca.markets/docs/oauth-tokens)
- [OpenAPI](openapi/alpaca-oauth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/alpaca-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/alpaca-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/alpacamarkets)
- [Portal](https://alpaca.markets/)
- [Documentation](https://docs.alpaca.markets/)
- [Pricing](https://alpaca.markets/data)
- [Git Hub](https://github.com/alpacahq)
- [Status Page](https://status.alpaca.markets/)
- [Terms of Service](https://alpaca.markets/legal)
- [Privacy Policy](https://alpaca.markets/privacy)
- [Plans](plans/alpaca-plans-pricing.yml)
- [Rate Limits](rate-limits/alpaca-rate-limits.yml)
- [Fin Ops](finops/alpaca-finops.yml)
- [Integrations](https://alpaca.markets/integrations)
- [L L Ms Txt](https://docs.alpaca.markets/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
