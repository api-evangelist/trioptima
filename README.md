# Trioptima (trioptima)

Trioptima provides post-trade infrastructure services for the OTC derivatives market, including portfolio compression (triReduce), portfolio reconciliation (triResolve), and risk mitigation services. Originally founded in 2000, Trioptima became part of OSTTRA in 2021 — a joint venture combining MarkitServ, Traiana, TriOptima, and Reset to form a comprehensive post-trade services platform. Trioptima's services help financial institutions reduce counterparty risk, optimize capital requirements, and meet regulatory obligations across interest rate, credit, FX, and equity derivatives.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml)

## Tags

- CME Group
- Derivatives
- Financial Services
- OSTTRA
- Portfolio Compression
- Post-Trade Services
- Reconciliation
- Risk Management

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Trioptima triReduce API

The triReduce API provides machine-to-machine access to TriOptima's portfolio compression cycles for OTC derivatives. The API allows cycle participants to automate participation in compression cycles, submit trade and risk data, and retrieve cycle results. Available for rates (IRS, OIS) and credit derivatives compression. Authentication uses OAuth 2.0 with read-only access for development and full access for production. Documentation available at https://rates.trireduce.com/api/v1/doc.

- **Human URL:** [https://osttra.com/services/optimisation/portfolio-compression/](https://osttra.com/services/optimisation/portfolio-compression/)
- **Base URL:** `https://rates.trireduce.com`

#### Tags

- Compression
- Derivatives
- Portfolio Optimization
- Risk Reduction

#### Properties

- [Documentation](https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api)
- [OpenAPI](openapi/trioptima-trireduce-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trioptima-trireduce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trioptima-trireduce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/trioptima-rules.yml)
- [Vocabulary](vocabulary/trioptima-vocabulary.yml)

### Trioptima triResolve Portfolio Reconciliation

Trioptima triResolve is a web-based portfolio reconciliation service for OTC derivatives. It normalizes trade data, reconciles all fields using an algorithmic match engine, and provides break workflow for identifying, tracking, investigating, and resolving discrepancies. Over 1,500 firms use triResolve for bilateral and cleared portfolio reconciliation. Data submission via SFTP API file transfer or manual upload (QuickPort).

- **Human URL:** [https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/](https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/)
- **Base URL:** `https://triResolve.com`

#### Tags

- Collateral Management
- Derivatives
- Disputes
- Reconciliation
- Risk Management

#### Properties

- [Documentation](https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/)
- [Postman Collection](collections/trioptima-trireduce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trioptima-trireduce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trioptima)
- [Website](https://osttra.com)
- [Website](https://osttra.com/login/trioptima-logins/)
- [Documentation](https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api)
- [Documentation](https://osttra.com/services/optimisation/portfolio-compression/)
- [Documentation](https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/)
- [Git Hub](https://github.com/TriOptima)
- [Git Hub](https://github.com/osttra)
- [J S O N L D Context](json-ld/trioptima-context.jsonld)
- [JSON Schema](json-schema/trioptima-compression-cycle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trioptima-trade-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/trioptima-vocabulary.yml)
- [Features](undefined)
- [Solutions](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
