# Trioptima

Trioptima provides post-trade infrastructure services for the OTC derivatives market, including portfolio compression (triReduce), portfolio reconciliation (triResolve), and risk mitigation services. Originally founded in 2000, Trioptima became part of OSTTRA in 2021 — a joint venture combining MarkitServ, Traiana, TriOptima, and Reset to form a comprehensive post-trade services platform.

**URL:** https://raw.githubusercontent.com/api-evangelist/trioptima/refs/heads/main/apis.yml

## Tags

CME Group, Derivatives, Financial Services, OSTTRA, Portfolio Compression, Post-Trade Services, Reconciliation, Risk Management

## APIs

### Trioptima triReduce API

Machine-to-machine access to TriOptima's portfolio compression service for OTC derivatives. Automates participation in compression cycles for interest rate swaps (IRS), OIS, and credit derivatives (CDS). Authentication uses OAuth 2.0.

**Human URL:** https://osttra.com/services/optimisation/portfolio-compression/  
**Base URL:** https://rates.trireduce.com/api/v1

#### Properties

| Type | URL |
|------|-----|
| Documentation | https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api |
| OpenAPI | [openapi/trioptima-trireduce-api-openapi.yml](openapi/trioptima-trireduce-api-openapi.yml) |
| Spectral Rules | [rules/trioptima-rules.yml](rules/trioptima-rules.yml) |

#### Tags

Compression, Derivatives, Portfolio Optimization, Risk Reduction

### Trioptima triResolve Portfolio Reconciliation

Web-based portfolio reconciliation service for OTC derivatives. Normalizes trade data, reconciles all fields algorithmically, and provides break workflow. Used by over 1,500 firms globally.

**Human URL:** https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/

## Artifacts

| Artifact | Path |
|----------|------|
| OpenAPI Spec | [openapi/trioptima-trireduce-api-openapi.yml](openapi/trioptima-trireduce-api-openapi.yml) |
| JSON Schema (Cycle) | [json-schema/trioptima-compression-cycle-schema.json](json-schema/trioptima-compression-cycle-schema.json) |
| JSON Schema (Trade) | [json-schema/trioptima-trade-schema.json](json-schema/trioptima-trade-schema.json) |
| JSON Structure | [json-structure/trioptima-compression-cycle-structure.json](json-structure/trioptima-compression-cycle-structure.json) |
| JSON-LD Context | [json-ld/trioptima-context.jsonld](json-ld/trioptima-context.jsonld) |
| Spectral Rules | [rules/trioptima-rules.yml](rules/trioptima-rules.yml) |
| Vocabulary | [vocabulary/trioptima-vocabulary.yml](vocabulary/trioptima-vocabulary.yml) |

## Examples

| Example | Path |
|---------|------|
| List Compression Cycles | [examples/trioptima-list-compression-cycles-example.json](examples/trioptima-list-compression-cycles-example.json) |
| Submit Cycle Trades | [examples/trioptima-submit-cycle-trades-example.json](examples/trioptima-submit-cycle-trades-example.json) |
| Get Cycle Results | [examples/trioptima-get-cycle-results-example.json](examples/trioptima-get-cycle-results-example.json) |

## Capabilities

| Capability | Description |
|-----------|-------------|
| [portfolio-compression](capabilities/portfolio-compression.yaml) | Full automation of OTC derivatives compression cycles via triReduce |

### Shared Definitions

| Shared Definition | API |
|-------------------|-----|
| [trireduce-api](capabilities/shared/trireduce-api.yaml) | Trioptima triReduce API |

## Common Properties

- [OSTTRA Website](https://osttra.com)
- [TriOptima Logins](https://osttra.com/login/trioptima-logins/)
- [triReduce API Documentation](https://www.cmegroup.com/education/brochures-and-handbooks/trireduce-api)
- [Portfolio Compression Service](https://osttra.com/services/optimisation/portfolio-compression/)
- [Portfolio Reconciliation Service](https://osttra.com/services/trade-lifecycle-services/portfolio-reconciliation/)
- [GitHub: TriOptima](https://github.com/TriOptima)
- [GitHub: OSTTRA](https://github.com/osttra)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
