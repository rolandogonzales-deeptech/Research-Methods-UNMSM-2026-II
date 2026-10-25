# MODEL CARD — AI Governance Maturity Assessment Model for Peruvian Organizations

**Course:** Research Methods and Scientific Integrity in AI — Session 7, UNMSM  
**Document status:** Research-stage specification; NOT a validated or deployed AI model  
**Version:** 0.1 (21 October 2026)  
**Research context:** Doctoral research in Deep Technologies  
**Regulatory/standards context:** Peruvian Law No. 31814 and NTP-ISO/IEC 42001:2025. Legal conformity has NOT been independently assessed.

> **Integrity statement:** This Model Card documents a proposed research model. The final architecture, dataset, experiments, quantitative results and validation remain to be determined. No measured accuracy, fairness, or compliance rates are claimed.

## 1. Model details

- **Working name:** AI Governance Maturity Assessment Model (Peru).
- **Purpose:** Support organizations in assessing the maturity of their AI governance processes and identifying improvement opportunities through partially automated evidence-based assessments.
- **Proposed inputs:** Structured questionnaire responses, documented organizational controls, AI inventories, policies, risk assessments and audit evidence, subject to authorization.
- **Proposed outputs:** Maturity assessment by governance dimension; evidence traceability; identified gaps; prioritized recommendations; confidence/insufficiency flags.
- **Methodology under investigation:** Rules and/or interpretable AI-assisted classification/scoring; final architecture and maturity scale **TO BE DEFINED AND VALIDATED**.
- **Training/fine-tuning:** **NOT PERFORMED / NOT DOCUMENTED**. A rule-based baseline may not require training.
- **Model owner and accountable reviewer:** **TO BE DESIGNATED** as part of the research protocol.

## 2. Intended use

**Intended:** Exploratory, decision-support assessments of AI governance maturity in consenting Peruvian organizations; identification of documentary and operational gaps; support for internal improvement planning and research evaluation.

**Not intended:** Certification of ISO/IEC 42001; issuance of legal compliance opinions; replacement of auditors, legal counsel or responsible governance personnel; autonomous sanctions, employment decisions, procurement exclusions or regulatory enforcement; processing confidential information without authorization.

**Human oversight:** A qualified reviewer must inspect evidence, contested classifications and recommendations before any consequential use.

## 3. Factors

Performance may vary by organization size, sector, public/private status, AI-use criticality, governance maturity, language of documents, completeness of evidence, and assessor experience. The proposed evaluation will report performance by at least **organization size** and **sector** when sample sizes permit. Where small samples make estimates unreliable, results will be labeled inconclusive. Representation across Peruvian regions and smaller organizations is a known sampling risk.

## 4. Metrics

**Planned, not yet measured:**

- Agreement with expert assessments: weighted Cohen's kappa (ordinal maturity levels), and/or intraclass correlation where appropriate.
- Classification performance for identified control gaps: precision, recall and F1; confusion matrix.
- Maturity score consistency: mean absolute error versus a predefined expert reference, if a numerical scale is validated.
- Evidence traceability: percentage of model claims linked to verifiable supporting records.
- Coverage and abstention: percentage of assessments flagged as insufficient evidence.
- Efficiency: assessment time and reviewer workload versus manual assessment.
- Reliability: mean ± standard deviation or confidence intervals over repeated evaluations; subgroup breakdowns.

**Actual results:** **NOT AVAILABLE — no evaluation dataset or locked test protocol has been supplied.**

## 5. Evaluation data

**Planned:** A held-out set of consenting organizational cases and/or expert-annotated governance scenarios, with separate development and evaluation sets. Case-level splitting is required so records from one organization cannot leak across partitions. Annotation protocol, sample size, dates, inclusion criteria, expert panel, adjudication and data access: **TO BE DEFINED**.

**Leakage prevention:** Fit any imputation, encoding, feature selection or learned transformation using training data only. Lock the evaluation protocol before final testing; prohibit using the test set for tuning.

## 6. Training data

**Status:** No finalized dataset or training corpus documented. Candidate sources include consented questionnaires, organizational evidence, and researcher-designed synthetic scenarios clearly marked as synthetic. Applicable regulatory/standard documents are reference materials, not automatically representative of real organizational practice. Collection, rights, privacy controls, annotation quality and sampling procedures must be specified before model development.

## 7. Quantitative analyses

| Analysis | Planned reporting | Current status |
|---|---|---|
| Overall performance | Primary metrics with 95% CI | NOT EVALUATED |
| Organization size | Micro/small/medium/large where supported | NO SUBGROUP DATA |
| Sector | Public/private and sector where supported | NO SUBGROUP DATA |
| Robustness | Missing evidence, contradictory records, document quality | NOT EVALUATED |
| Baseline comparison | Expert-only/manual process vs proposed model, matched cases | NOT EVALUATED |
| Ablation | Remove automated scoring, evidence mapping or recommendation component one at a time, where implemented | NOT EVALUATED |

**Fair benchmarking commitment:** Same cases, scoring rubric and evaluation protocol for the baseline and proposed model; matched assessment budget where feasible. Repeat stochastic experiments over at least five fixed seeds, if stochastic training is used. Report negative/null results as well as gains.

## 8. Ethical considerations

- **Privacy/confidentiality:** Organizational governance records may contain sensitive business or personal information. Obtain authorization; minimize, pseudonymize, restrict access and define retention/deletion procedures.
- **Bias and exclusion:** A tool trained on large, well-resourced organizations may underestimate maturity in smaller or regional entities. Audit representativeness and subgroup outcomes.
- **Automation bias:** A maturity score is an aid, not an authoritative judgment; require human review and allow challenges/corrections.
- **Explainability and accountability:** Each finding should identify the assessment criterion, cited evidence, reviewer and model/version used.
- **Legal/standards caution:** Alignment with Law No. 31814 and NTP-ISO/IEC 42001:2025 is a research objective; this document is not proof of regulatory compliance or certification.

## 9. Caveats and recommendations

1. **Do not deploy for operational compliance decisions** before expert validation, ethics/privacy review and external testing.
2. Finalize maturity dimensions, scoring anchors and the applicable legal/standards mapping with qualified experts.
3. Document dataset provenance, licensing, consent, collection procedures and quality assurance.
4. Preregister confirmatory hypotheses, metrics and subgroup analyses; clearly label exploratory findings.
5. Compare against a strong manual/rule-based baseline and perform component ablations.
6. Release reproducible code, configuration, seeds and anonymized or synthetic evaluation artifacts where lawful.
7. Update this card with actual metrics, limitations, model version and monitoring responsibilities after experiments.

**References for document structure:** Mitchell et al. (2019), *Model Cards for Model Reporting*. Session 7 lecture materials, UNMSM.  
**Research-specific statements:** Proposed design for doctoral research; they are not established experimental findings.
