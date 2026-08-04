# NocoDB (nocodb)

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

NocoDB is an open-source, self-hostable alternative to Airtable that turns any relational database — MySQL, PostgreSQL, Microsoft SQL Server, or SQLite — into a collaborative smart spreadsheet. It exposes a versioned REST API (v2 and v3) with separate Data APIs for record CRUD operations and Meta APIs for managing workspaces, bases, tables, fields, views, and attachments. Authentication is handled via API tokens or session auth tokens, with Swagger UI bundled into every instance for live exploration. NocoDB is available as a free community self-hosted deployment or as a managed cloud service with tiered plans ranging from Free to Enterprise.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/nocodb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nocodb/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nocodb-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nocodb-api-evangelist&utm_content=repo)

## Tags

- Database
- No-Code
- Low-Code
- Airtable Alternative
- Open Source
- Spreadsheet
- REST API
- Self-Hosted

## APIs

| Name | Description |
|------|-------------|
| NocoDB Data API | RESTful API for querying and manipulating records across tables and views in any NocoDB base. Supports full CRUD on rows, filtering, pagination, sorting, field selection, and bulk operations. Available in v2 and v3. |
| NocoDB Meta API | RESTful API for managing NocoDB metadata including workspaces, bases, tables, fields, views, hooks (webhooks), scripts, and user permissions. Higher-tier plan features require Business or Enterprise. |

## Plans / Rate Limits / FinOps

| Resource | Path |
|----------|------|
| Plans & Pricing | [plans/nocodb-plans-pricing.yml](plans/nocodb-plans-pricing.yml) |
| Rate Limits | [rate-limits/nocodb-rate-limits.yml](rate-limits/nocodb-rate-limits.yml) |
| FinOps | [finops/nocodb-finops.yml](finops/nocodb-finops.yml) |

**Pricing summary:** Free (cloud, 3 editors / 1 k records / 1 k API calls/mo) · Plus $12/seat/mo · Business $24/seat/mo · Scale $45/seat/mo · Enterprise (custom). Self-hosted Community edition is free and unlimited.

**Rate limits:** 5 requests/second per user across all plans. HTTP 429 returned on breach; default retry window is 30 seconds.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://nocodb.com/ |
| Documentation | https://nocodb.com/docs/product-docs/developer-resources/rest-apis |
| GitHub Organization | https://github.com/nocodb |
| LinkedIn | https://www.linkedin.com/company/nocodb |
| Blog | https://nocodb.com/blog |
| Pricing | https://nocodb.com/pricing |
| Status Page | https://status.nocodb.com/ |
| Changelog | https://nocodb.com/changelog |
| X | https://x.com/nocodb |
| SDK (npm) | https://www.npmjs.com/package/nocodb-sdk |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
