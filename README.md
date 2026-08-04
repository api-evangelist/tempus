# Tempus (tempus)

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
