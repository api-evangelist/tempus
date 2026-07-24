# Tempus (tempus)

Tempus AI, Inc. (formerly Tempus Labs) is an AI-enabled precision medicine and genomic diagnostics company founded in 2015 by Eric Lefkofsky and headquartered in Chicago, Illinois (NASDAQ: TEM). Tempus has assembled one of the world's largest libraries of clinical and molecular data and runs a next-generation-sequencing lab offering oncology assays including Tempus xT (solid-tumor DNA), xF (cell-free DNA liquid biopsy), xG (germline), and whole-transcriptome RNA, expanding from oncology into cardiology, neuropsychiatry, radiology, and infectious disease.

For its United States home market, Tempus delivers its technical surface as gated provider and partner integrations rather than a public self-serve developer program. No public developer portal, downloadable OpenAPI, or anonymously reachable FHIR CapabilityStatement was found during review — integration is provisioned through provider and partner onboarding.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tempus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tempus/refs/heads/main/apis.yml)

## Tags

- Healthcare
- United States
- Genomics
- Precision Medicine
- Clinical AI
- Oncology
- FHIR
- HL7
- EHR
- Interoperability
- Life Sciences
- Real-World Data

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Tempus EHR Integration (Tempus Edge)

Tempus Edge is a secure gateway that establishes bidirectional interfaces with provider EHRs using HL7, FHIR, API, and PACS connectivity, so genomic test orders and results flow directly inside the clinical workflow of systems such as Epic, Oracle Health / Cerner, and OncoEMR. Access is provider/partner onboarded; no downloadable OpenAPI or public FHIR CapabilityStatement is published.

- **Human URL:** [https://www.tempus.com/solutions/ehr-integration/](https://www.tempus.com/solutions/ehr-integration/)

#### Tags

- EHR
- FHIR
- HL7
- Interoperability

#### Properties

- [Documentation](https://www.tempus.com/solutions/ehr-integration/)
- [Documentation](https://www.tempus.com/oncology/ehr-integration/)

### Tempus Hub

Tempus Hub is a secure online portal for providers to order genomic and molecular tests, track order status, and view comprehensive patient results, available on desktop and mobile. It is an authenticated provider application; no public API reference is documented.

- **Human URL:** [https://www.tempus.com/solutions/hub/](https://www.tempus.com/solutions/hub/)

#### Tags

- Genomics
- Oncology
- Portal

#### Properties

- [Documentation](https://www.tempus.com/solutions/hub/)
- [Documentation](https://www.tempus.com/order/)

### Tempus Lens Platform

Tempus Lens is an agentic-AI platform for oncology drug development that combines a large de-identified multimodal real-world dataset with Tempus oncology foundation models, AI agents, and scientific workflows. It is commercially available as a login-gated SaaS application at lens.tempus.ai; no public developer API is documented.

- **Human URL:** [https://lens.tempus.ai](https://lens.tempus.ai)

#### Tags

- Clinical AI
- Real-World Data
- Life Sciences

#### Properties

- [Documentation](https://www.tempus.com/life-sciences/real-world-data/)

## Common Properties

- [Website](https://www.tempus.com/)
- [GitHub Organization](https://github.com/tempuslabs)
- [Documentation](https://www.tempus.com/resources/document-library/)
- [Getting Started](https://www.tempus.com/providers/)
- [Blog](https://www.tempus.com/news/)

## Review

No public developer portal, downloadable OpenAPI, or anonymously reachable FHIR CapabilityStatement / SMART-on-FHIR configuration was found. Tempus markets HL7 and FHIR as transports used by Tempus Edge for EHR integration, but the FHIR endpoint is partner-provisioned and no public conformance resource is published. See [review.yml](review.yml) for full findings.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
