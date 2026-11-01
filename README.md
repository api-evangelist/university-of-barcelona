# University of Barcelona

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

The University of Barcelona (Universitat de Barcelona, UB) is a public research university founded in 1450 in Barcelona, Catalonia, Spain, ranked #165 in the QS World University Rankings 2025. UB operates no central developer portal, no public API program and no confirmed organization-wide GitHub account, and its main web estate at www.ub.edu sits behind a Cloudflare bot challenge that returns HTTP 403 to any automated client. What it does operate is a genuine, machine-readable institutional footprint that is easy to miss because none of it is marketed as an API: a SAML 2.0 identity provider published through RedIRIS SIR into eduGAIN with the ub.edu attribute scope; an LTI 1.3 Advantage tool platform on its self-hosted Moodle at campusvirtual.ub.edu, with a live JWKS and token endpoint; an OAI-PMH 2.0 data provider over 100 journal sets at revistes.ub.edu; a DSpace 7.6.6 repository at diposit.ub.edu that was live in June 2026 and returned 503 across every probe on 2026-09-01; and a Crossref membership for the university press. Its research-data repository and library discovery layer are tenancies on consortium and vendor platforms operated by CSUC and Ex Libris, not UB engineering, and are recorded here as relationships rather than as UB contracts.

**Areas:** University · Higher Education · Education · Spain · Catalonia · Identity Federation · SAML · Shibboleth · eduGAIN · LTI · LMS · OAI-PMH

## University of Barcelona on APIs.io

Everything profiled for University of Barcelona is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-barcelona/](https://apis.io/providers/university-of-barcelona/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [UB SAML 2.0 Identity Provider (RedIRIS SIR / eduGAIN)](https://apis.io/apis/university-of-barcelona/ub-idp-edugain/) — The University of Barcelona's own SAML 2.0 identity provider, published as a signed EntityDescriptor through RedIRIS SIR — the Spanish academic identity…
- [Campus Virtual UB (Moodle) — LTI 1.3 Advantage platform and Web Services](https://apis.io/apis/university-of-barcelona/campusvirtual-moodle/) — UB's self-hosted Moodle learning platform on the university's own host. It acts as an LTI 1.3 tool platform: the JWKS at /mod/lti/certs.php serves a live…
- [Revistes Científiques de la UB (OJS) — OAI-PMH 2.0](https://apis.io/apis/university-of-barcelona/revistes-ojs/) — Open Journal Systems platform self-hosted by UB at revistes.ub.edu, publishing the university's scholarly journals. Its OAI-PMH 2.0 data provider answers…
- [UB Centralized SSO (Identificació UB, SAML 2.0 / CAS)](https://apis.io/apis/university-of-barcelona/sso-saml/) — Universitat de Barcelona centralized single sign-on providing federated authentication for university web applications, on UB's own host. The SAML2…
- [Dipòsit Digital REST API (DSpace 7)](https://apis.io/apis/university-of-barcelona/diposit-rest/) — DSpace 7.6.6 REST API for the Dipòsit Digital de la Universitat de Barcelona, UB's institutional repository of teaching, research and institutional output,…
- [Dipòsit Digital OAI-PMH](https://apis.io/apis/university-of-barcelona/diposit-oai/) — OAI-PMH metadata-harvesting endpoint for the Dipòsit Digital de la Universitat de Barcelona, used for harvesting into national aggregators and the CRAI…
- [CORA Repositori de Dades de Recerca — Universitat de Barcelona collection](https://apis.io/apis/university-of-barcelona/cora-rdr-ub/) — UB's named research-data collection on CORA RDR, the Dataverse 6.10.1 instance operated by CSUC (Consorci de Serveis Universitaris de Catalunya) for the…
- [Cercabib — CRAI library discovery (Ex Libris Primo VE, view 34CSUC_UB)](https://apis.io/apis/university-of-barcelona/cercabib-primo/) — The CRAI library discovery layer for UB, delivered on Ex Libris Primo VE under the CSUC shared Alma tenancy. The UB view is 34CSUC_UB:VU1 and it resolves on…
- [Crossref membership — Edicions de la Universitat de Barcelona (member 17854)](https://apis.io/apis/university-of-barcelona/crossref-member/) — The University of Barcelona press is a Crossref member in its own right: member id 17854, DOI prefixes 10.1344 and 10.32869, 10,561 registered DOIs at probe…
- [ROR registration — Universitat de Barcelona (021018s57)](https://apis.io/apis/university-of-barcelona/ror-registration/) — The University of Barcelona's entry in the Research Organization Registry. ROR id https://ror.org/021018s57, display name "Universitat de Barcelona",…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Barcelona Context](https://apis.io/jsonld/university-of-barcelona/university-of-barcelona-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Barcelona Domain Security](https://apis.io/security/university-of-barcelona/university-of-barcelona-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Barcelona Plans Pricing](https://apis.io/plans/university-of-barcelona/university-of-barcelona-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Barcelona Rate Limits](https://apis.io/rate-limits/university-of-barcelona/university-of-barcelona-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Barcelona Finops](https://apis.io/finops/university-of-barcelona/university-of-barcelona-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ub.edu/)

## API Evangelist rating

**Kin Score 16.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 18.0 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-barcelona/](https://apis.io/providers/university-of-barcelona/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Barcelona: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-barcelona/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
