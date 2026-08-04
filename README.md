# Solventum

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

Solventum is a Fortune 500 healthcare company spun off from 3M in 2024, focused on healthcare technology including medical-surgical solutions, dental and orthodontic products, health information systems, and purification and filtration technologies.

**URL:** [https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/solventum/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Dental, EHR, Electronic Health Records, Healthcare, Healthcare IT, Health Information Systems, Medical Devices, Medical Technology

## APIs

### Health Information Systems API

Clinical coding, DRG grouping, computer-assisted coding, and revenue cycle management APIs integrating with Epic, Cerner, Oracle Health, and other EHR systems.

- **Documentation:** [https://www.solventum.com/en-us/home/health-information-systems/](https://www.solventum.com/en-us/home/health-information-systems/)

### Clinical Documentation Improvement API

APIs for computer-assisted CDI workflows, real-time physician query generation, and documentation quality analysis.

- **Documentation:** [https://www.solventum.com/en-us/home/health-information-systems/clinical-documentation-integrity/](https://www.solventum.com/en-us/home/health-information-systems/clinical-documentation-integrity/)

## Artifacts

### JSON Schemas

- [json-schema/solventum-clinical-encounter-schema.json](json-schema/solventum-clinical-encounter-schema.json) — Clinical encounter with diagnoses, procedures, and notes
- [json-schema/solventum-coding-result-schema.json](json-schema/solventum-coding-result-schema.json) — CAC coding result with DRG assignment and quality flags

### JSON Structure

- [json-structure/solventum-his-structure.json](json-structure/solventum-his-structure.json) — Health Information Systems core data entity structures

### JSON-LD

- [json-ld/solventum-context.jsonld](json-ld/solventum-context.jsonld) — Linked data context mapping to HL7 FHIR and schema.org

### Examples

- [examples/solventum-clinical-encounter-example.json](examples/solventum-clinical-encounter-example.json) — Inpatient STEMI encounter for coding
- [examples/solventum-coding-result-example.json](examples/solventum-coding-result-example.json) — CAC result with DRG 246 assignment

### Vocabulary

- [vocabulary/solventum-vocabulary.yml](vocabulary/solventum-vocabulary.yml) — Health Information Systems domain vocabulary

## Common Properties

- [Website](https://www.solventum.com)
- [Health Information Systems](https://www.solventum.com/en-us/home/health-information-systems/)
- [Blog / Newsroom](https://www.solventum.com/en-us/home/about-solventum/newsroom/)
- [Investors](https://investors.solventum.com/)
- [LinkedIn](https://www.linkedin.com/company/solventum/)
- [Contact / Support](https://www.solventum.com/en-us/home/contact-us/)
- [Privacy Policy](https://www.solventum.com/en-us/home/privacy/)
- [Terms of Use](https://www.solventum.com/en-us/home/terms-of-use/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
