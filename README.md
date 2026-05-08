# Firebolt (firebolt)

Firebolt is a cloud data warehouse with elastic engines and consumption-based pricing. It exposes a REST API for issuing SQL queries and managing engines/databases, plus language SDKs (Python, Node.js, Java, .NET) and an OAuth service-account flow.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/firebolt/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=firebolt-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Firebolt REST API** - SQL queries and engine/database management at `https://api.app.firebolt.io`. OAuth 2.0 client_credentials at `https://id.app.firebolt.io/oauth/token` with audience `https://api.firebolt.io`.

## Tags
- Data Warehouse, Cloud, SQL, Analytics

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.firebolt.io/)
- [Documentation](https://docs.firebolt.io/)
- [Pricing](https://www.firebolt.io/pricing)
- [Plans](plans/firebolt-plans-pricing.yml)
- [RateLimits](rate-limits/firebolt-rate-limits.yml)
- [FinOps](finops/firebolt-finops.yml)

## Notes
- Pricing reconciled (research): $0.35/FBU/hour compute (per-second billing), $23/TiB-month storage on AWS S3. $200 trial credit for first 30 days. Firebolt Core is the free self-hosted edition.
- No publicly documented per-account REST API rate limit; concurrency bounded by engine size.
- Service-account OAuth flow (`client_credentials`) issues short-lived bearer tokens.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
