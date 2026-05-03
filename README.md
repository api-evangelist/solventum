# Solventum

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
