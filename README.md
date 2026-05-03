# Tax Reporting Templates

Pre-built templates and frameworks for generating tax reports, compliance documents, and financial summaries required for tax filing and regulatory purposes. Covers IRS Modernized e-File (MeF) schemas, sales tax compliance APIs, payroll tax forms, and corporate tax reporting standards.

## APIs

### IRS Modernized e-File (MeF) API
The primary federal e-filing system. Defines XML schemas and business rules for individual (1040), corporate (1120), partnership (1065), and employment tax forms (941, 940).

- **Docs:** [https://www.irs.gov/tax-professionals/e-file-providers-partners/modernized-e-file](https://www.irs.gov/tax-professionals/e-file-providers-partners/modernized-e-file)
- **Schemas:** [https://www.irs.gov/e-file-providers/modernized-e-file-mef-schemas-and-business-rules](https://www.irs.gov/e-file-providers/modernized-e-file-mef-schemas-and-business-rules)

### TaxJar API
REST API for real-time sales tax calculations, nexus tracking, and automated filing for 20,000+ businesses.

- **Docs:** [https://developers.taxjar.com/](https://developers.taxjar.com/)

### Avalara AvaTax API
Global tax calculation and compliance API covering 27 API groups including calculations, returns, tariffs, and international tax.

- **Docs:** [https://developer.avalara.com/](https://developer.avalara.com/)

### W-2 and 1099 Reporting Templates
Templates for annual payroll (W-2) and contractor income (1099-NEC, 1099-MISC) reporting.

- **Docs:** [https://www.irs.gov/businesses/small-businesses-self-employed/employment-taxes](https://www.irs.gov/businesses/small-businesses-self-employed/employment-taxes)

## Artifacts

### JSON Schemas
| Schema | File |
|--------|------|
| Tax Report | [json-schema/tax-report-schema.json](json-schema/tax-report-schema.json) |

### JSON Structure
| Structure | File |
|-----------|------|
| Tax Report Structure | [json-structure/tax-report-structure.json](json-structure/tax-report-structure.json) |

### JSON-LD Context
| Context | File |
|---------|------|
| Tax Reporting Context | [json-ld/tax-reporting-templates-context.jsonld](json-ld/tax-reporting-templates-context.jsonld) |

### Examples
| Example | File |
|---------|------|
| Annual Tax Report (1040) | [examples/tax-annual-report-example.json](examples/tax-annual-report-example.json) |

### Vocabulary
| Vocabulary | File |
|-----------|------|
| Tax Reporting Vocabulary | [vocabulary/tax-reporting-templates-vocabulary.yml](vocabulary/tax-reporting-templates-vocabulary.yml) |

## Tags

Compliance, Documentation, Finance, Reporting, Tax, Templates
