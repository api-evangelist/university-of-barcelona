# University of Barcelona (university-of-barcelona)

The University of Barcelona (Universitat de Barcelona, UB) is a public research university founded in 1450 in Barcelona, Catalonia, Spain, ranked #165 in the QS World University Rankings 2025. This repository catalogs UB's publicly verifiable developer/API footprint as an [APIs.json](https://apisjson.org) provider profile for the api-evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-barcelona/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-barcelona-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Spain, Catalonia, Open Data, Library, Scholarly, Repository, DSpace, OAI-PMH

## APIs

- **Dipòsit Digital REST API (DSpace 7)** — Public DSpace 7.6.6 REST API for the UB institutional repository. Docs: https://diposit.ub.edu/server/api
- **Dipòsit Digital OAI-PMH** — Metadata-harvesting endpoint for the institutional repository. Docs: https://diposit.ub.edu/server/oai/request?verb=Identify
- **UB Centralized SSO (SAML 2.0 / CAS)** — Federated authentication service for university applications; gated to registered apps. Docs: https://www.ub.edu/portal/web/iub/detallservei/-/recurs/1051544/autenticacio-centralitzada-sso-

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-barcelona-plans-pricing.yml](plans/university-of-barcelona-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-barcelona-rate-limits.yml](rate-limits/university-of-barcelona-rate-limits.yml)
- FinOps: [finops/university-of-barcelona-finops.yml](finops/university-of-barcelona-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ub.edu/
- LinkedIn: https://www.linkedin.com/school/university-of-barcelona/
- Authentication: https://sso.ub.edu/SAML2/SSOService.php
- Plans, RateLimits, FinOps, Review (see files above)

## Notes

All endpoints listed were probed live during cataloging on 2026-06-03. The Dipòsit Digital REST API and OAI-PMH endpoints returned HTTP 200 with valid DSpace/OAI metadata; the SSO SAML2 endpoint returned HTTP 200 but is restricted to registered institutional applications. The UB transparency open-data page (web.ub.edu) returned HTTP 403 to automated fetching though it exists in a browser. No central branded developer portal and no confirmed official organization-wide GitHub account were found — only course/research repositories. Nothing in this profile was fabricated; only confirmed, public properties are recorded.

## Maintainers

- Kin Lane — kin@apievangelist.com
