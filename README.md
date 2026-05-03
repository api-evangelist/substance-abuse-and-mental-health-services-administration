# Substance Abuse and Mental Health Services Administration (samhsa)
SAMHSA is a branch of the U.S. Department of Health and Human Services dedicated to improving the quality and availability of prevention, treatment, and recovery support services for individuals struggling with substance abuse and mental health disorders. SAMHSA provides APIs and open data including the behavioral health treatment services locator, national survey data, treatment statistics, and state mental health data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Federal Government, Public Health, Behavioral Health, Substance Use Disorders, Mental Health, Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-02

## APIs

### SAMHSA Behavioral Health Treatment Services Locator API
Search over 14,000 treatment facilities by location, service type, and payment options. Powers findtreatment.gov. No API key required.

**Human URL:** [https://findtreatment.gov](https://findtreatment.gov)

#### Tags:
 - Treatment Facilities, Behavioral Health, Substance Use Disorders, Mental Health, Open Data

#### Properties

- [Documentation](https://findtreatment.gov)
- [National Helpline](https://www.samhsa.gov/find-help/national-helpline)
- [OpenAPI](openapi/samhsa-treatment-locator-openapi.yml)

---

### SAMHSA Data Portal
National and state behavioral health statistics including NSDUH survey data, treatment episode data, and mental health service utilization data.

**Human URL:** [https://www.datafiles.samhsa.gov](https://www.datafiles.samhsa.gov)

#### Tags:
 - Open Data, Survey Data, NSDUH, Statistics, Public Health

#### Properties

- [Documentation](https://www.datafiles.samhsa.gov)
- [Data Portal](https://www.samhsa.gov/data/)

---

### SAMHSA Mental Health Client Level Data
Client-level data from state mental health agencies on clients receiving state-funded services.

#### Tags:
 - Mental Health, Client Data, Statistics, Open Data

---

## Common Properties

- [Website](https://www.samhsa.gov)
- [Treatment Locator](https://findtreatment.gov)
- [Data Portal](https://www.samhsa.gov/data/)
- [National Helpline (1-800-662-4357)](https://www.samhsa.gov/find-help/national-helpline)
- [988 Suicide & Crisis Lifeline](https://988lifeline.org)
- [GitHub Organization](https://github.com/samhsa)
- [Data.gov Catalog](https://catalog.data.gov/dataset?organization=samhsa-hhs)
- [Vocabulary](vocabulary/samhsa-vocabulary.yml)
- [JSON-LD Context](json-ld/samhsa-context.jsonld)

## JSON Schemas

- [samhsa-treatment-facility-schema.json](json-schema/samhsa-treatment-facility-schema.json) — Treatment facility data model
- [samhsa-nsduh-data-schema.json](json-schema/samhsa-nsduh-data-schema.json) — NSDUH survey data record schema

## JSON Structures

- [samhsa-treatment-facility-structure.json](json-structure/samhsa-treatment-facility-structure.json) — Treatment facility API response structure

## JSON-LD

- [samhsa-context.jsonld](json-ld/samhsa-context.jsonld) — Semantic context aligned with schema.org

## Examples

- [Search Treatment Facilities](examples/samhsa-search-treatment-facilities-example.json)

## Key Datasets

| Dataset | Description | Format |
|---|---|---|
| NSDUH | National Survey on Drug Use and Health | SAS, SPSS, Stata, CSV |
| TEDS | Treatment Episode Data Set | SAS, SPSS, Stata |
| N-SSATS | National Survey of Substance Abuse Treatment Services | CSV |
| CLD | Mental Health Client Level Data | CSV |
| State Estimates | State-level behavioral health estimates | CSV |

## Crisis Resources

- **National Helpline:** 1-800-662-HELP (4357) — Free, confidential, 24/7
- **988 Suicide & Crisis Lifeline:** Call or text 988
- **Crisis Text Line:** Text HOME to 741741

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
