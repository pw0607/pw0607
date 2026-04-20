# Pooja Walia

## AI Safety, Compliance, and Risk Engineering

I build open-source tools and contribute to federal standards that make AI governance practical for regulated industries -- healthcare, government, defense, and critical infrastructure. I also work on open data governance and transparency for public health, because responsible AI starts with responsible data.

---

### What I Build

**Automated AI Compliance Evaluation**
Systems that assess AI against NIST AI RMF, HIPAA, FedRAMP, NIST CSF, ISO 27001, OWASP LLM Top 10, and GDPR. Structured prompt pipelines evaluate each control individually, produce evidence-based verdicts, and generate severity-weighted remediation plans.

**Healthcare AI Safety Tooling**
AI systems processing patient data carry real consequences when they fail. I build tooling that validates PHI protection, access controls, encryption, audit logging, and breach notification procedures against HIPAA requirements -- catching gaps before they become incidents.

**IoT Device Security for Federal Environments**
Contributing secure boot, firmware integrity verification, safety-critical isolation, network segmentation, vulnerability disclosure, and SBOM requirements to federal IoT cybersecurity standards -- addressing gaps in how connected devices are secured in healthcare and government networks.

**Healthcare Privacy Engineering**
Building de-identification workflows, privacy risk assessments, and anonymization tooling for patient data -- applying HIPAA Safe Harbor, Expert Determination, K-Anonymity, and the NIST Privacy Risk Assessment Methodology (PRAM) to real healthcare data flows.

**Open Data Governance and Transparency**
Contributing to federal open data plans that shape how health and human services data is collected, shared, and governed. Improving documentation quality, metadata standards alignment, and accessibility so that public datasets are findable, usable, and trustworthy for researchers, developers, and the public.

---

### Contributions to Federal Standards and Open Data

#### [NIST FederalProfile-8259A](https://github.com/usnistgov/FederalProfile-8259A) -- IoT Device Cybersecurity

6 contributions to the federal IoT cybersecurity capability catalog:

| Contribution | Area | What It Addresses |
|-------------|------|-------------------|
| Secure boot and firmware integrity verification | Technical / Secure Execution | No boot integrity capability existed for federal IoT devices |
| Safety-critical isolation for medical devices | Technical / Secure Device Operation | Cybersecurity failures could disrupt patient safety in healthcare IoT |
| Data minimization for IoT devices | Technical / Data Protection | HIPAA minimum necessary standard had no IoT equivalent in the catalog |
| Vulnerability disclosure policies | Nontechnical / Security | No coordinated disclosure capability per OMB M-20-32 and EO 14028 |
| SBOM software transparency | Nontechnical / Security | EO 14028 mandates SBOM; FDA requires it for medical devices |
| Network segmentation support | Technical / Secure Communication | NIST SP 800-53 SC-7 boundary protection had no IoT device-side capability |

#### [NIST PrivacyEngCollabSpace](https://github.com/usnistgov/PrivacyEngCollabSpace) -- Privacy Engineering

3 healthcare-focused contributions:

| Contribution | Type | What It Addresses |
|-------------|------|-------------------|
| Hospital EHR de-identification for research | Use Case | First entry in the empty de-identification use cases directory; covers HIPAA Safe Harbor, K-Anonymity, synthetic data, NER-based text de-identification |
| Healthcare de-identification with ARX | Tool | HIPAA-specific configuration guide for the ARX anonymization tool; no existing tool addressed healthcare de-identification workflows |
| Healthcare patient data privacy risk assessment | Use Case | NIST PRAM applied to patient data flows (EHR, research sharing, HIE); only the second risk assessment use case in the repository |

#### [HHS Living Open Data Plan](https://github.com/HHS/living-hhs-open-data-plan) -- Open Data Governance

9 contributions improving documentation quality, data governance transparency, and public accessibility of the federal open data plan for health and human services:

| Contribution | Type | What It Addresses |
|-------------|------|-------------------|
| Replace tracking-wrapped URLs with direct links | PR [#10](https://github.com/HHS/living-hhs-open-data-plan/pull/10) | Footnote URLs contained Outlook SafeLinks wrappers that obscure destinations and may break over time |
| Fix typos and grammar across plan documents | PR [#11](https://github.com/HHS/living-hhs-open-data-plan/pull/11) | Incorrect acronym (RWE listed as RWD), missing preposition, verb disagreement, and doubled letter |
| Convert data tables from bullet lists to Markdown | PR [#12](https://github.com/HHS/living-hhs-open-data-plan/pull/12) | Three tables labeled as tables but formatted as bullets; inconsistent spacing in data columns |
| Duplicate footnote numbers across appendices | Issue [#13](https://github.com/HHS/living-hhs-open-data-plan/issues/13) | Footnote IDs collide when appendices are rendered as a single document |
| DCAT-US 3.0 migration checklist for data consumers | Issue [#14](https://github.com/HHS/living-hhs-open-data-plan/issues/14) | No public schema change documentation for external systems consuming HHS metadata |
| Community accessibility audit of top datasets | Issue [#15](https://github.com/HHS/living-hhs-open-data-plan/issues/15) | Section 508 compliance covers websites but not the datasets themselves |
| Publish Data Governance Board meeting records | Issue [#16](https://github.com/HHS/living-hhs-open-data-plan/issues/16) | Plan commits to public DGB meetings but no mechanism for publishing agendas or minutes |
| International health data interoperability section | Issue [#17](https://github.com/HHS/living-hhs-open-data-plan/issues/17) | Plan references Brazil's LGPD but lacks broader cross-border data exchange discussion |
| Community use cases subsection for public engagement | Issue [#18](https://github.com/HHS/living-hhs-open-data-plan/issues/18) | No showcase of how external organizations use HHS open data in practice |

---

### Featured Project

#### [AI Compliance Copilot](https://github.com/pw0607/ai-compliance-copilot)

Production-quality, multi-framework AI compliance evaluation system.

| Capability | Detail |
|-----------|--------|
| Frameworks | NIST AI RMF, HIPAA, NIST CSF, FedRAMP, ISO 27001, OWASP LLM Top 10, GDPR |
| Controls | 70 total, each with critical/high/medium/low severity |
| Remediation | Priority-ranked action plans (risk score x severity weight) |
| Comparison | Evaluate against multiple frameworks simultaneously |
| History | Track compliance posture changes across audits |
| Export | PDF reports + structured JSON for stakeholder documentation |
| Testing | 34 automated tests with full API coverage |
| Stack | Python, FastAPI, Streamlit, Docker |

---

### Technical Focus

- **AI Governance Automation** -- executable compliance checks derived from NIST AI RMF, EO 14110 guidance, and HIPAA security rules
- **Open Data Governance** -- improving metadata standards, documentation quality, and public accessibility of federal health datasets under the Evidence Act and OPEN Government Data Act
- **IoT Cybersecurity Standards** -- secure boot, SBOM, vulnerability disclosure, and safety-critical isolation for federal device catalogs
- **Healthcare Privacy Engineering** -- de-identification, risk assessment, and data minimization for patient data under HIPAA
- **Severity-Weighted Risk Scoring** -- quantified metrics that map control gaps to remediation priority
- **LLM Security** -- prompt injection detection, output validation, and agency controls aligned with OWASP LLM Top 10
- **Open-Source Compliance** -- making AI safety, privacy, and data governance tooling accessible to organizations that can't afford proprietary GRC platforms

---

### By the Numbers

| | |
|---|---|
| 7 | Compliance frameworks automated |
| 70 | Individual controls with severity ratings |
| 18 | Contributions to federal standards and open data (6 IoT security + 3 privacy engineering + 9 open data governance) |
| 34 | Automated tests passing |
| 3 | Federal repos contributed to: NIST, HHS |
| 4 | Regulated sectors covered: healthcare, government, finance, defense |

---

### Philosophy

Compliance shouldn't be a checkbox exercise. AI systems in healthcare and government carry real consequences when they fail. I build tools that surface gaps early, quantify risk clearly, and give teams a concrete path to fix what matters most.

Good governance extends beyond AI models to the data that feeds them. Public health data should be open by default, well-documented, accessible, and governed transparently -- so that researchers, developers, and citizens can trust what they're building on.

The best compliance tool is one that makes doing the right thing easier than ignoring it.

---

### Connect

- GitHub: [@pw0607](https://github.com/pw0607)
