# SEC EDGAR

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

The U.S. Securities and Exchange Commission (SEC) EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides free public access to corporate financial filings submitted to the SEC. The EDGAR REST API at data.sec.gov delivers JSON-formatted data without requiring authentication or API keys, covering company submissions, XBRL financial facts, and company concept data. Endpoints support CIK lookups, full filing history, structured XBRL financial disclosures across reporting periods, and cross-company comparative frames for US-GAAP and IFRS taxonomies.

**Areas:** Financial Data · SEC · EDGAR · Public Company Filings · XBRL · Regulatory · Government · Financial Reporting · Company Submissions · Securities · Government Data

## SEC EDGAR on APIs.io

Everything profiled for SEC EDGAR is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sec/](https://apis.io/providers/sec/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [SEC EDGAR Company Concept API](https://apis.io/apis/sec/sec-company-concept-api/) — Historical values for a single XBRL concept
- [SEC EDGAR Company Facts API](https://apis.io/apis/sec/sec-company-facts-api/) — XBRL financial disclosures for a company
- [SEC EDGAR Operational Status API](https://apis.io/apis/sec/sec-edgar-operational-status-api-api/) — This API reports the status of the EDGAR system. This resource requires presentation of a Filer API Token only.
- [SEC EDGAR Filer Management API](https://apis.io/apis/sec/sec-filer-management-api-api/) — A set of API endpoints that allows you to verify permissions, get filer information, manage CCC, manage individuals, and manage delegations.
- [SEC EDGAR Frames API](https://apis.io/apis/sec/sec-frames-api/) — Cross-company data for a concept in a specific period
- [SEC EDGAR Search API](https://apis.io/apis/sec/sec-search-api/) — Full-text search across EDGAR filing documents
- [SEC EDGAR Submission API](https://apis.io/apis/sec/sec-submission-api-api/) — Submission of filings to EDGAR by API can be made through the Submission API. The Submission API requires the presentation of a Filer API Token in…
- [SEC EDGAR Submission Status API](https://apis.io/apis/sec/sec-submission-status-api-api/) — The Submission Status API provides information from the EDGAR system. It requires a Filer API Token and accession number(s). To obtain information about a…
- [SEC EDGAR Submissions API](https://apis.io/apis/sec/sec-submissions-api/) — Company filing history and metadata by CIK
- [SEC EDGAR Company Filings API](https://apis.io/apis/sec/sec-edgar-company-filings-api/) — The SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides REST APIs for accessing company filings, XBRL financial data, and…
- [SEC EDGAR Full-Text Search API](https://apis.io/apis/sec/sec-full-text-search-api/) — Full-text search across all EDGAR filings
- [SEC EDGAR XBRL API](https://apis.io/apis/sec/sec-xbrl-api/) — Structured XBRL financial data

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sec Agentic Access](https://apis.io/agentic-access/sec/sec-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [SEC EDGAR Company Submissions](https://apis.io/schemas/sec/sec-company-submissions/)
- [SEC EDGAR XBRL Fact Value](https://apis.io/schemas/sec/sec-xbrl-fact-value/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Sec Context](https://apis.io/jsonld/sec/sec-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [SEC EDGAR API Vocabulary](https://apis.io/vocabularies/sec/sec-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Sec Company Submissions Example](https://apis.io/examples/sec/sec-company-submissions-example/)
- [Sec Xbrl Company Concept Example](https://apis.io/examples/sec/sec-xbrl-company-concept-example/)
- [Sec Xbrl Frames Example](https://apis.io/examples/sec/sec-xbrl-frames-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [SEC EDGAR Data Company Concept API](https://apis.io/collections/sec/open-sec-company-concept-api/)
- [SEC EDGAR Data Company Concept Company Facts API](https://apis.io/collections/sec/open-sec-company-facts-api/)
- [SEC EDGAR Data Company Concept EDGAR Operational Status API API](https://apis.io/collections/sec/open-sec-edgar-operational-status-api-api/)
- [SEC EDGAR Data Company Concept Filer Management API API](https://apis.io/collections/sec/open-sec-filer-management-api-api/)
- [SEC EDGAR Data Company Concept Frames API](https://apis.io/collections/sec/open-sec-frames-api/)
- [SEC EDGAR Data Company Concept Search API](https://apis.io/collections/sec/open-sec-search-api/)
- [SEC EDGAR Data Company Concept Submission API API](https://apis.io/collections/sec/open-sec-submission-api-api/)
- [SEC EDGAR Data Company Concept Submission Status API API](https://apis.io/collections/sec/open-sec-submission-status-api-api/)
- [SEC EDGAR Data Company Concept Submissions API](https://apis.io/collections/sec/open-sec-submissions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [SEC EDGAR — jsonschema rules](https://apis.io/rules/sec/sec-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Sec Authentication](https://apis.io/security/sec/sec-authentication/)
- [Sec Domain Security](https://apis.io/security/sec/sec-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sec Plans Pricing](https://apis.io/plans/sec/sec-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sec Rate Limits](https://apis.io/rate-limits/sec/sec-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Sec Finops](https://apis.io/finops/sec/sec-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.sec.gov)
- [Documentation](https://www.sec.gov/edgar/sec-api-documentation)
- [Pricing](https://www.sec.gov/edgar/sec-api-documentation)
- [Blog](https://www.sec.gov/newsroom)

## API Evangelist rating

**Kin Score 35.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 62.9 |
| Contract governance | 23.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 31.0 |
| Access clarity | 15.8 |

**Agent readiness 28.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
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

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sec/](https://apis.io/providers/sec/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SEC EDGAR: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sec/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
