# Pooja Walia

## AI Safety, Compliance, and Risk Engineering

I build open-source tools and contribute to federal standards that make AI governance practical for regulated industries -- healthcare, government, defense, and critical infrastructure.

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

---

### Contributions to Federal Standards

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
- **IoT Cybersecurity Standards** -- secure boot, SBOM, vulnerability disclosure, and safety-critical isolation for federal device catalogs
- **Healthcare Privacy Engineering** -- de-identification, risk assessment, and data minimization for patient data under HIPAA
- **Severity-Weighted Risk Scoring** -- quantified metrics that map control gaps to remediation priority
- **LLM Security** -- prompt injection detection, output validation, and agency controls aligned with OWASP LLM Top 10
- **Open-Source Compliance** -- making AI safety and privacy tooling accessible to organizations that can't afford proprietary GRC platforms

---

### By the Numbers

| | |
|---|---|
| 7 | Compliance frameworks automated |
| 70 | Individual controls with severity ratings |
| 9 | Contributions to NIST federal standards (6 IoT security + 3 privacy engineering) |
| 34 | Automated tests passing |
| 4 | Regulated sectors covered: healthcare, government, finance, defense |

---

### Philosophy

Compliance shouldn't be a checkbox exercise. AI systems in healthcare and government carry real consequences when they fail. I build tools that surface gaps early, quantify risk clearly, and give teams a concrete path to fix what matters most.

The best compliance tool is one that makes doing the right thing easier than ignoring it.

---

### Connect

- GitHub: [@pw0607](https://github.com/pw0607)
