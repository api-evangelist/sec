# SEC EDGAR (sec)

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
