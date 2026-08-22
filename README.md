# Oracle Primavera (oracle-primavera)

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

Oracle Primavera is a portfolio of project portfolio management (PPM) applications for construction, engineering, and capital project industries. Primavera APIs provide programmatic access to enterprise project portfolio management data including WBS structures, activity schedules, resource assignments, critical path analysis, and portfolio dashboards across cloud and on-premises deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-primavera/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Construction
- Engineering
- Project Management
- Scheduling
- Portfolio Management
- Oracle

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Oracle Primavera P6 EPPM REST API

Oracle Primavera P6 EPPM REST API provides programmatic access to enterprise project portfolio management data including WBS structures, activity schedules, resource assignments, critical path analysis, and portfolio dashboards. Available for both cloud and on-premises deployments. Documentation covers version 6.2.1 through version 26 (2026).

- **Human URL:** [https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html](https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html)
- **Base URL:** `https://{host}/p6ws/rest/v1`

#### Tags

- Construction
- EPPM
- Project Management
- REST
- Scheduling

#### Properties

- [Documentation](https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html)
- [Reference](https://docs.oracle.com/cd/G48897_01/index.htm)
- [Changelog](https://docs.oracle.com/cd/E64687_01/EPPM/EPPM_CFO.html)
- [OpenAPI](openapi/oracle-primavera-p6-eppm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-primavera-p6-eppm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-primavera-p6-eppm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Primavera Gateway Integration API

Oracle Primavera Gateway provides integration APIs for connecting Primavera P6 with other Oracle and third-party applications. Enables bi-directional data exchange for projects, resources, cost accounts, and activity data between P6 EPPM and ERP, asset management, and financial systems.

- **Human URL:** [https://docs.oracle.com/en/industries/construction-engineering/primavera-gateway/index.html](https://docs.oracle.com/en/industries/construction-engineering/primavera-gateway/index.html)

#### Tags

- Construction
- Integration
- Project Management
- Scheduling
- XML

#### Properties

- [Documentation](https://docs.oracle.com/en/industries/construction-engineering/primavera-gateway/index.html)
- [Postman Collection](collections/oracle-primavera-p6-eppm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-primavera-p6-eppm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Primavera Analytics API

Oracle Primavera Analytics provides reporting and business intelligence APIs for portfolio performance insights, project health dashboards, resource utilization analysis, and earned value management reporting across construction and engineering portfolios.

- **Human URL:** [https://docs.oracle.com/en/industries/construction-engineering/primavera-analytics/index.html](https://docs.oracle.com/en/industries/construction-engineering/primavera-analytics/index.html)

#### Tags

- Analytics
- Construction
- Project Management
- Reporting
- Scheduling

#### Properties

- [Documentation](https://docs.oracle.com/en/industries/construction-engineering/primavera-analytics/index.html)
- [Postman Collection](collections/oracle-primavera-p6-eppm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-primavera-p6-eppm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Primavera P6 Scheduling API

Oracle Primavera P6 provides project scheduling and portfolio management APIs for construction, engineering, and capital projects. REST and XML APIs enable access to WBS structures, activity schedules, resource assignments, and critical path analysis.

- **Human URL:** [https://docs.oracle.com/en/industries/construction-engineering/primavera/](https://docs.oracle.com/en/industries/construction-engineering/primavera/)

#### Tags

- Construction
- Project Management
- Scheduling
- XML

#### Properties

- [Documentation](https://docs.oracle.com/en/industries/construction-engineering/primavera/)
- [Postman Collection](collections/oracle-primavera-p6-eppm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-primavera-p6-eppm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/oracle)
- [Portal](https://docs.oracle.com/en/industries/construction-engineering/primavera/)
- [Website](https://www.oracle.com/construction-engineering/primavera/)
- [Documentation](https://docs.oracle.com/en/industries/construction-engineering/primavera-p6-project/index.html)
- [Reference](https://docs.oracle.com/cd/G48897_01/index.htm)
- [Changelog](https://docs.oracle.com/cd/E64687_01/EPPM/EPPM_CFO.html)
- [Getting Started](https://mylearn.oracle.com/construction)
- [Support](https://www.oracle.com/support/)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [OpenAPI](openapi/oracle-primavera-p6-eppm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N  Schema](json-schema/oracle-primavera-project-schema.json)
- [J S O N  Schema](json-schema/oracle-primavera-activity-schema.json)
- [J S O N- L D  Context](json-ld/oracle-primavera-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
