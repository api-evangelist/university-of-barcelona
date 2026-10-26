# University of Barcelona (university-of-barcelona)

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

The University of Barcelona (Universitat de Barcelona, UB) is a public research university founded in 1450 in Barcelona, Catalonia, Spain, ranked #165 in the QS World University Rankings 2025. This repository catalogs UB's publicly verifiable developer/API footprint as an [APIs.json](https://apisjson.org) provider profile for the api-evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-barcelona/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-barcelona-api-evangelist&utm_content=repo

## Type

- university (Public Research University)
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Spain, Catalonia, Identity Federation, SAML, Shibboleth, eduGAIN, LTI, Learning Management, OAI-PMH, Repository, DSpace, Research Data, Library, Scholarly, Crossref, Open Access

## Surfaces, by operator

Every surface carries an `x-operator` saying **who runs the thing it describes** — which for a
university is very often not the institution. `institution` means UB's own host and UB's own
deployment; `federation` means UB's own identity carried in a shared academic federation;
`tenant` means UB's named account or collection on someone else's platform; `registry` means an
identifier registry UB is registered in. Vendor contracts are not saved here.

### institution

- **Campus Virtual UB (Moodle) — LTI 1.3 Advantage platform and Web Services** — self-hosted Moodle acting as an LTI 1.3 tool platform. JWKS live at https://campusvirtual.ub.edu/mod/lti/certs.php (200); LTI Advantage token endpoint live at /mod/lti/token.php (400 invalid_request to an empty body); Moodle Web Services REST enabled and token-gated.
- **Revistes Científiques de la UB (OJS) — OAI-PMH 2.0** — https://revistes.ub.edu/index.php/index/oai (200). Identify, ListSets (100 sets) and ListMetadataFormats all answer. OJS REST API v1 present but key-gated (403).
- **UB Centralized SSO (Identificació UB)** — https://sso.ub.edu/SAML2/SSOService.php (200); gated to registered institutional applications.
- **Dipòsit Digital REST API (DSpace 7.6.6)** — https://diposit.ub.edu/server/api — **degraded**: HTTP 503 host-wide on every probe 2026-09-01; was 200 on 2026-06-03.
- **Dipòsit Digital OAI-PMH** — https://diposit.ub.edu/server/oai/request — **degraded**, same host-wide outage.

### federation

- **UB SAML 2.0 Identity Provider** — entityID `https://www.rediris.es/sir/ubidp`, published as signed metadata through RedIRIS SIR, the Spanish academic identity federation, and carried into eduGAIN. `shibmd:Scope` ub.edu, mdui:DisplayName "Universitat de Barcelona", registrationAuthority http://www.rediris.es/. Live 2026-09-01 (200, text/xml). This is UB's strongest machine-readable surface.

### tenant

- **CORA Repositori de Dades de Recerca — UB collection** — https://dataverse.csuc.cat/dataverse/UB. Dataverse 6.10.1 operated by CSUC; the collection (alias UB, contact crai-recerca@ub.edu) is UB's, the API contract is not.
- **Cercabib — CRAI library discovery** — Ex Libris Primo VE view `34CSUC_UB:VU1` under the CSUC shared Alma tenancy.

### registry

- **Crossref member 17854** — Edicions de la Universitat de Barcelona; DOI prefixes 10.1344 and 10.32869; 10,561 DOIs.
- **ROR 021018s57** — Universitat de Barcelona; resolves to OpenAlex I71999127.

## Education regime conformance

Probed against the Kin Score `education` regime `standards[]`. Five of twelve evidenced by live
probe — see [conformance/university-of-barcelona-education-standards.yml](conformance/university-of-barcelona-education-standards.yml).

| Standard | Status | Evidence |
|---|---|---|
| `lti` | conformant | Moodle LTI 1.3 JWKS + Advantage token endpoint |
| `saml` | conformant | Signed SAML 2.0 IdP metadata in RedIRIS SIR / eduGAIN |
| `shibboleth` | conformant | `shibmd:Scope` ub.edu in the UB entity descriptor |
| `oai-pmh` | conformant | OJS OAI-PMH 2.0, 100 sets |
| `crossref` | conformant | Crossref member 17854 |
| `datacite` | not found | Zero DataCite clients resolve to UB; DOIs mint via CSUC |
| `orcid`, `scim`, `oneroster`, `ed-fi`, `caliper`, `qti` | not found | No endpoint located |

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-barcelona-plans-pricing.yml](plans/university-of-barcelona-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-barcelona-rate-limits.yml](rate-limits/university-of-barcelona-rate-limits.yml)
- FinOps: [finops/university-of-barcelona-finops.yml](finops/university-of-barcelona-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.ub.edu/ (Cloudflare bot challenge — 403 to automated clients)
- LinkedIn: https://www.linkedin.com/school/university-of-barcelona/
- IdentityFederation: https://www.rediris.es/sir/ubidp
- ResearchRepository: https://dataverse.csuc.cat/dataverse/UB
- LibraryCatalog: https://cercabib.ub.edu/discovery/search?vid=34CSUC_UB:VU1
- Authentication: https://sso.ub.edu/SAML2/SSOService.php
- Conformance, DomainSecurity, Plans, RateLimits, FinOps, Review, JSONLD (see files above)

## Notes

Re-profiled 2026-09-01 under the API Evangelist university pipeline, which settles operator
attribution before saving anything. UB publishes **no OpenAPI, AsyncAPI or other machine-readable
API contract anywhere**, operates no developer portal and no public API program, and has no
confirmed organization-wide GitHub account. No specification was generated for it and nothing was
fabricated.

Three findings qualify the picture. The central web estate — www.ub.edu, web.ub.edu and the
transparency open-data pages — sits behind a Cloudflare bot challenge returning HTTP 403 with
`cf-mitigated: challenge` even to a full browser User-Agent, so the open-data portal could not be
read and no `OpenData` pointer is claimed. The whole diposit.ub.edu host returned an Apache 503
maintenance page on every probe across the run, over both HTTP and HTTPS; both DSpace surfaces are
retained and marked degraded rather than deleted, because a 503 is an outage and not a retirement.
And CSUC's Dataverse `/api/` paths began 302-redirecting to a CSUC Google Sites landing page under
request rate — a redirect that reads as a live 200 if followed blindly.

What the June 2026 profile missed, and this one records, is that UB's real programmable footprint is
identity and teaching infrastructure rather than data APIs: a federated SAML 2.0 IdP in eduGAIN, an
LTI 1.3 Advantage platform, and an OAI-PMH data provider. None of it is marketed as an API.

## Maintainers

- Kin Lane — kin@apievangelist.com
