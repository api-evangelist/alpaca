# Alpaca (alpaca)

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
