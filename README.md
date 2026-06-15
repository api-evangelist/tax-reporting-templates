# Tax Reporting Templates (tax-reporting-templates)

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
