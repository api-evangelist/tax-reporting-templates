# Tax Reporting Templates (tax-reporting-templates)

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

Pre-built templates and frameworks for generating tax reports, compliance documents, and financial summaries required for tax filing and regulatory purposes. Covers IRS Modernized e-File (MeF) schemas, sales tax compliance APIs (TaxJar, Avalara, TaxCloud), payroll tax forms, and corporate tax reporting standards. Helps organizations meet regulatory requirements and demonstrate accountability to stakeholders.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tax-reporting-templates/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tax-reporting-templates/refs/heads/main/apis.yml)

## Tags

- Compliance
- Documentation
- Finance
- Reporting
- Tax
- Templates

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### IRS Modernized e-File (MeF) API

The IRS Modernized e-File (MeF) system is the primary e-filing platform for federal tax returns. It defines XML schemas and business rules for individual, business, and employment tax forms. Software developers use these schemas to build compliant tax preparation and filing software.

- **Human URL:** [https://www.irs.gov/tax-professionals/e-file-providers-partners/modernized-e-file](https://www.irs.gov/tax-professionals/e-file-providers-partners/modernized-e-file)
- **Base URL:** `https://la1.www4.irs.gov/mef`

#### Tags

- Compliance
- E-File
- Federal Tax
- IRS
- Tax

#### Properties

- [Documentation](https://www.irs.gov/tax-professionals/e-file-providers-partners/modernized-e-file)
- [Documentation](https://www.irs.gov/e-file-providers/modernized-e-file-mef-schemas-and-business-rules)
- [Guide](https://www.irs.gov/pub/irs-pdf/p4164.pdf)
- [Postman Collection](collections/tax-reporting-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tax-reporting-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TaxJar API

TaxJar provides a REST API for real-time sales tax calculations, nexus tracking, and automated tax filing. It supports more than 20,000 businesses across all US states and integrates with major e-commerce platforms.

- **Human URL:** [https://developers.taxjar.com/](https://developers.taxjar.com/)
- **Base URL:** `https://api.taxjar.com/v2`

#### Tags

- Compliance
- Sales Tax
- Tax

#### Properties

- [Documentation](https://developers.taxjar.com/)
- [Postman Collection](collections/tax-reporting-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tax-reporting-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Avalara AvaTax API

Avalara AvaTax API provides global tax calculation, compliance, and reporting for businesses operating across multiple jurisdictions. Supports 27 API groups including calculations, returns, documents, fiscal, tariffs, and international tax.

- **Human URL:** [https://developer.avalara.com/](https://developer.avalara.com/)
- **Base URL:** `https://rest.avatax.com/api/v2`

#### Tags

- Compliance
- Global Tax
- Sales Tax
- Tax

#### Properties

- [Documentation](https://developer.avalara.com/)
- [Postman Collection](collections/tax-reporting-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tax-reporting-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W-2 and 1099 Reporting Templates

Templates and schemas for generating IRS W-2 (wages and tax statements) and 1099 (miscellaneous income) forms required for annual payroll and contractor reporting.

- **Human URL:** [https://www.irs.gov/businesses/small-businesses-self-employed/employment-taxes](https://www.irs.gov/businesses/small-businesses-self-employed/employment-taxes)

#### Tags

- 1099
- Compliance
- Payroll
- Tax
- W-2

#### Properties

- [Documentation](https://www.irs.gov/businesses/small-businesses-self-employed/employment-taxes)
- [Postman Collection](collections/tax-reporting-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tax-reporting-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.irs.gov/)
- [J S O N  Schema](json-schema/tax-report-schema.json)
- [J S O N  Structure](json-structure/tax-report-structure.json)
- [JSON-LD](json-ld/tax-reporting-templates-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/tax-reporting-templates-vocabulary.yml)
