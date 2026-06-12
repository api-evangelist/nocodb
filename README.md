# NocoDB (nocodb)

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
