# SEC EDGAR (sec)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The U.S. Securities and Exchange Commission (SEC) EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides free public access to corporate financial filings submitted to the SEC. The EDGAR REST API at data.sec.gov delivers JSON-formatted data without requiring authentication or API keys, covering company submissions, XBRL financial facts, and company concept data. Endpoints support CIK lookups, full filing history, structured XBRL financial disclosures across reporting periods, and cross-company comparative frames for US-GAAP and IFRS taxonomies.

APIs.json: https://raw.githubusercontent.com/api-evangelist/sec/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sec-api-evangelist&utm_content=repo

## Tags

Financial Data, SEC, EDGAR, Public Company Filings, XBRL, Regulatory, Government, Financial Reporting, Company Submissions, Securities

## APIs

- **SEC EDGAR Data API** - RESTful access to public company submissions, XBRL financial facts, company concepts, and cross-company frames via data.sec.gov
- **SEC EDGAR Full-Text Search API** - Full-text search across all EDGAR filings by content, form type, entity name, and date via efts.sec.gov
- **SEC EDGAR Filer Management API** - Authenticated filer submission, status, and account management for registered EDGAR filers via api.edgarfiling.sec.gov

## Plans, Rate Limits, and FinOps

- **Plans:** [plans/sec-plans-pricing.yml](plans/sec-plans-pricing.yml) — Single free public tier; no API key, no fees, no registration required
- **Rate Limits:** [rate-limits/sec-rate-limits.yml](rate-limits/sec-rate-limits.yml) — 10 requests per second per IP; User-Agent header required
- **FinOps:** [finops/sec-finops.yml](finops/sec-finops.yml) — Zero direct API cost; infrastructure and optimization guidance for consumers

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.sec.gov |
| Documentation | https://www.sec.gov/edgar/sec-api-documentation |
| Developer | https://www.sec.gov/about/developer-resources |
| GitHub Org | https://github.com/sec-gov |
| LinkedIn | https://www.linkedin.com/company/us-securities-and-exchange-commission |
| Blog / Newsroom | https://www.sec.gov/newsroom |
| X (Twitter) | https://x.com/SEC_News |

## Maintainers

- Kin Lane &lt;kin@apievangelist.com&gt;
