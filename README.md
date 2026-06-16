# HHS (US Department of Health and Human Services) (hhs)

The US Department of Health and Human Services provides data APIs for health programs, public health datasets, grants data, and interoperability standards for health information. HHS operates a broad ecosystem of APIs spanning FDA drug and device data, grants opportunity search, health IT open data, HRSA health center locators, and public health content syndication through its agencies including FDA, HRSA, ONC, and ODPHP.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hhs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hhs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Health
- Public Health
- Grants
- Interoperability
- FHIR
- Government
- Open Data
- FDA
- HRSA
- ONC

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### openFDA API

OpenFDA provides RESTful APIs and raw download access to high-value FDA public datasets including drug adverse events, drug labels, drug recalls, medical device 510(k) clearances, device classifications, device recalls, and food recall enforcement reports. Free API key available for higher rate limits.

- **Human URL:** [https://open.fda.gov/apis/](https://open.fda.gov/apis/)
- **Base URL:** `https://api.fda.gov`

#### Tags

- FDA
- Drugs
- Medical Devices
- Food Safety
- Adverse Events
- Recalls

#### Properties

- [Documentation](https://open.fda.gov/apis/)
- [Authentication](https://open.fda.gov/apis/authentication/)
- [Rate Limits](rate-limits/openfda.yml)
- [Plans](plans/openfda.yml)

### Simpler Grants.gov API

The Simpler Grants.gov API provides programmatic access to search and retrieve federal grant opportunities. Supports keyword search, fielded search, pagination, sorting, and detailed opportunity retrieval. Requires an API key managed through a developer account.

- **Human URL:** [https://simpler.grants.gov/developers](https://simpler.grants.gov/developers)
- **Base URL:** `https://api.simpler.grants.gov`

#### Tags

- Grants
- Federal Funding
- Opportunities
- Search

#### Properties

- [Documentation](https://simpler.grants.gov/developers)
- [OpenAPI](https://api.simpler.grants.gov/docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I Spec](openapi/simpler-grants-gov.yml)
- [JSON Schema](json-schema/opportunityv1.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/opportunitysearchresponsev1.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agencyv1.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/errorresponse.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/paginationinfo.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/healthcheckresponse.json) — [JSON Schema](https://json-schema.org/specification)
- [Examples](examples/v1_opportunities_search_post_request.json)
- [Examples](examples/v1_agencies_search_post_request.json)
- [J S O N L D Context](json-ld/context.json)
- [Rate Limits](rate-limits/simpler-grants.yml)
- [Plans](plans/simpler-grants.yml)

### MyHealthfinder API

The MyHealthfinder API (Version 4) allows developers to add evidence-based, plain language health content to their websites and applications. Content is available in English and Spanish and is completely free to use. Provides personalized health recommendations based on age, sex, and pregnancy status.

- **Human URL:** [https://odphp.health.gov/our-work/national-health-initiatives/health-literacy/consumer-health-content/free-web-content/apis-developers](https://odphp.health.gov/our-work/national-health-initiatives/health-literacy/consumer-health-content/free-web-content/apis-developers)
- **Base URL:** `https://health.gov/myhealthfinder`

#### Tags

- Public Health
- Health Content
- Consumer Health
- ODPHP

#### Properties

- [Documentation](https://odphp.health.gov/our-work/national-health-initiatives/health-literacy/consumer-health-content/free-web-content/apis-developers/api-documentation)

### ONC Health IT Open Data API

The ONC Health IT Open Data API provides access to open datasets published by the Office of the National Coordinator for Health Information Technology. Supports filtering by state and year, and returns data in JSON, CSV, or XML formats. Covers datasets on EHR adoption, health IT use, and interoperability metrics.

- **Human URL:** [https://healthit.gov/data/api/](https://healthit.gov/data/api/)
- **Base URL:** `https://healthit.gov/data/open-api`

#### Tags

- Health IT
- EHR
- Interoperability
- ONC
- Open Data

#### Properties

- [Documentation](https://healthit.gov/data/api/)

### HRSA Health Center Data Web Service

The HRSA Health Center Data Web Service allows querying for federally qualified health centers by state, county, or ZIP code. A separate service provides access to Ryan White HIV/AIDS Medical Care Providers searchable by latitude and longitude. Uses SOAP/XML. Registration required to obtain a web token.

- **Human URL:** [https://data.hrsa.gov/data/services](https://data.hrsa.gov/data/services)
- **Base URL:** `https://data.hrsa.gov`

#### Tags

- HRSA
- Health Centers
- HIV/AIDS
- Provider Locator
- SOAP

#### Properties

- [Documentation](https://data.hrsa.gov/data/services)

### HealthData.gov Catalog API

The HealthData.gov Catalog API uses CKAN and provides machine-readable access to the HHS health data catalog. Developers can find newly added datasets, search the catalog, download catalog metadata for analysis, or build new catalog tools. Conforms to DCAT-US 3.0 standards.

- **Human URL:** [https://healthdata.gov/](https://healthdata.gov/)
- **Base URL:** `https://healthdata.gov/api/3`

#### Tags

- Open Data
- CKAN
- Health Data
- Data Catalog
- DCAT

#### Properties

- [Documentation](https://healthdata.gov/)

## Common Properties

- [Git Hub](https://github.com/HHS)
- [Terms of Service](https://www.hhs.gov/web/policies-and-standards/hhs-web-policies/terms-of-service/index.html)
- [Privacy Policy](https://www.hhs.gov/web/policies-and-standards/hhs-web-policies/privacy/index.html)
- [Open Data](https://healthdata.gov/)
- [Status](https://www.hhs.gov/)
- [Blog](https://www.hhs.gov/about/news/index.html)
- [Accessibility](https://www.hhs.gov/web/policies-and-standards/hhs-web-policies/accessibility/index.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
