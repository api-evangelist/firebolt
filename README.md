# Firebolt (firebolt)

Firebolt is a cloud data warehouse with elastic engines and consumption-based pricing. It exposes a REST API for issuing SQL queries and managing engines/databases, plus language SDKs (Python, Node.js, Java, .NET) and an OAuth service-account flow.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/firebolt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/firebolt/refs/heads/main/apis.yml)

## Tags

- Data Warehouse
- Cloud
- SQL
- Analytics

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Firebolt REST API

The Firebolt REST API issues SQL queries against running engines and manages account, engine, and database resources. Authentication is OAuth 2.0 client_credentials against `https://id.app.firebolt.io/oauth/token` with audience `https://api.firebolt.io`, using a service account ID and secret. Tokens are sent as `Authorization: Bearer <access_token>`.

- **Human URL:** [https://docs.firebolt.io/guides/run-queries/using-the-api](https://docs.firebolt.io/guides/run-queries/using-the-api)
- **Base URL:** `https://api.app.firebolt.io`

#### Tags

- SQL
- Query
- Engine Management

#### Properties

- [Documentation](https://docs.firebolt.io/guides/run-queries/using-the-api)
- [Authentication](https://docs.firebolt.io/Guides/managing-your-organization/service-accounts.html)
- [SDK](https://python-sdk.docs.firebolt.io/)
- [Postman Collection](collections/firebolt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/firebolt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/firebolt-db)
- [LinkedIn](https://www.linkedin.com/company/firebolt)
- [Website](https://www.firebolt.io/)
- [Portal](https://docs.firebolt.io/)
- [Pricing](https://www.firebolt.io/pricing)
- [Plans](plans/firebolt-plans-pricing.yml)
- [Rate Limits](rate-limits/firebolt-rate-limits.yml)
- [Fin Ops](finops/firebolt-finops.yml)
- [Integrations](https://www.firebolt.io/integrations)
- [L L Ms Txt](https://docs.firebolt.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
