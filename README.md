# Substance Abuse and Mental Health Services Administration (substance-abuse-and-mental-health-services-administration)

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

The Substance Abuse and Mental Health Services Administration (SAMHSA) is a branch of the U.S. Department of Health and Human Services dedicated to improving the quality and availability of prevention, treatment, and recovery support services for individuals struggling with substance abuse and mental health disorders. SAMHSA provides APIs and open data for the behavioral health treatment services locator, national survey data (NSDUH), treatment episode statistics (TEDS), and state mental health data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/substance-abuse-and-mental-health-services-administration/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Public Health
- Behavioral Health
- Substance Use Disorders
- Mental Health
- Open Data
- Healthcare

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### SAMHSA Behavioral Health Treatment Services Locator API

The SAMHSA Treatment Services Locator API provides searchable access to over 14,000 behavioral health treatment facilities across the United States. Search by location, service type, payment options (Medicaid, Medicare, sliding fee, free treatment), and population served. Powers the findtreatment.gov website.

- **Human URL:** [https://findtreatment.gov](https://findtreatment.gov)

#### Tags

- Treatment Facilities
- Behavioral Health
- Substance Use Disorders
- Mental Health
- Open Data

#### Properties

- [Documentation](https://findtreatment.gov)
- [National  Helpline](https://www.samhsa.gov/find-help/national-helpline)
- [OpenAPI](openapi/samhsa-treatment-locator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/samhsa-treatment-locator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/samhsa-treatment-locator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAMHSA Data Portal

SAMHSA's data portal provides access to national and state-level behavioral health statistics including the National Survey on Drug Use and Health (NSDUH), Treatment Episode Data Set (TEDS), and National Survey of Substance Abuse Treatment Services (N-SSATS). Data available for download in SAS, SPSS, and Stata formats.

- **Human URL:** [https://www.datafiles.samhsa.gov](https://www.datafiles.samhsa.gov)

#### Tags

- Open Data
- Survey Data
- NSDUH
- Statistics
- Public Health

#### Properties

- [Documentation](https://www.datafiles.samhsa.gov)
- [Data  Portal](https://www.samhsa.gov/data/)
- [State  Data](https://pdas.samhsa.gov/sapt)
- [Postman Collection](collections/samhsa-treatment-locator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/samhsa-treatment-locator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAMHSA Mental Health Client Level Data

Client-Level Data (CLD) from state mental health agencies on clients receiving state-funded mental health services. Provides data on demographics, diagnoses, services received, and outcomes.

- **Human URL:** [https://www.samhsa.gov/data/report/2020-mental-health-client-level-data-cld](https://www.samhsa.gov/data/report/2020-mental-health-client-level-data-cld)

#### Tags

- Mental Health
- Client Data
- Statistics
- Open Data

#### Properties

- [Documentation](https://www.samhsa.gov/data/report/2020-mental-health-client-level-data-cld)
- [Postman Collection](collections/samhsa-treatment-locator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/samhsa-treatment-locator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/substance-abuse-and-mental-health-services-administration)
- [Website](https://www.samhsa.gov)
- [Treatment  Locator](https://findtreatment.gov)
- [Data  Portal](https://www.samhsa.gov/data/)
- [Data  Files](https://www.datafiles.samhsa.gov)
- [National  Helpline](https://www.samhsa.gov/find-help/national-helpline)
- [988  Suicide &  Crisis  Lifeline](https://988lifeline.org)
- [F A Q](https://www.samhsa.gov/about-us/who-we-are/faq)
- [Terms of  Use](https://www.samhsa.gov/data/terms-use)
- [Privacy Policy](https://www.samhsa.gov/privacy)
- [GitHub Organization](https://github.com/samhsa)
- [Data.gov  Catalog](https://catalog.data.gov/dataset?organization=samhsa-hhs)
- [API Reference](https://api.data.gov/docs/samhsa/)
- [Vocabulary](vocabulary/samhsa-vocabulary.yml)
- [J S O N- L D  Context](json-ld/samhsa-context.jsonld)
- [J S O N  Schema](json-schema/samhsa-treatment-facility-schema.json)
- [J S O N  Schema](json-schema/samhsa-nsduh-data-schema.json)
- [J S O N  Structure](json-structure/samhsa-treatment-facility-structure.json)
- [Example](examples/samhsa-search-treatment-facilities-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
