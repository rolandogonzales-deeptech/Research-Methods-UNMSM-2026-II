# DATASET DATASHEET — Proposed AI Governance Maturity Assessment Dataset (Peru)

**Course:** Research Methods and Scientific Integrity in AI — Session 7, UNMSM  
**Dataset status:** PROPOSED; not yet collected, finalized or published  
**Version:** 0.1 (21 October 2026)  
**Associated model:** AI Governance Maturity Assessment Model for Peruvian Organizations

> **Integrity statement:** This document specifies a dataset collection and stewardship plan. There is currently **no verified number of organizations, rows, observations, labels or class distribution** to report. Unavailable information is marked explicitly rather than invented.

## 1. Motivation

**Why create it?** To study whether structured organizational evidence can support reproducible, interpretable and partially automated evaluation of AI governance maturity in Peru. The research addresses a practical skills and evidence-assessment gap faced by organizations adopting AI.

**Who is responsible?** Researcher and participating organizations, with institutional and ethics oversight **TO BE CONFIRMED**. Funding, data controller/processor roles and conflicts of interest **UNKNOWN — TO INVESTIGATE**.

**Target use:** Doctoral research, benchmarking of assessment methods and analysis of maturity dimensions; not a substitute for certification or legal review.

## 2. Composition

**Proposed unit of analysis:** An organizational AI-governance assessment at a specified date, with linked control-level evidence records.

**Candidate fields:** Pseudonymous organization ID; sector; size band; assessment date; AI-use profile; governance-control identifier; documentary evidence status; assessor rating; justification; evidence provenance; expert-adjudicated maturity level (if validated); missingness and uncertainty flags.

**Labels:** Ordinal maturity levels and/or gap/no-gap labels **TO BE DEFINED**, including written scoring anchors and expert adjudication rules.

**Dataset size, distribution, geographic coverage, class balance and missingness:** **UNKNOWN — DATA NOT COLLECTED**.

**Potentially sensitive fields:** Business processes, risk registers, vendor information, employee details and internal policies. Direct personal identifiers and trade secrets should be excluded or minimized wherever possible.

## 3. Collection

**Planned collection routes:** Authorized questionnaires/interviews, governance-document review, structured evidence checklists and, if useful, clearly separated synthetic scenarios for software testing.

**Sampling:** Seek variation in public/private organizations, industry, size and geography. Inclusion/exclusion criteria, recruitment method, sampling frame and target N **TO BE PRE-REGISTERED OR DOCUMENTED**.

**Consent and authorization:** Obtain appropriate organizational permissions and, where personal data are involved, applicable consent/legal basis and ethics approvals before collection. Do not assume access rights to proprietary evidence.

**Annotation:** At least two suitably qualified assessors for a subset or all cases, with a documented rubric and disagreement-resolution procedure; actual staffing and reliability results **NOT YET AVAILABLE**.

**Collection dates, devices/platforms, response rates and incentives:** **UNKNOWN — TO INVESTIGATE**.

## 4. Preprocessing

**Proposed:** Remove direct identifiers; assign pseudonymous organization IDs; standardize response categories and timestamps; record source and document versions; check duplicates; define missing-value codes; validate contradictory entries; retain audit logs.

**Leakage controls:** Split by organization, not individual evidence record; do not fit imputers/encoders/selectors on all data before splitting. Keep expert adjudication for the test set independent of model predictions.

**Quality controls:** Double-review selected labels, report inter-rater agreement, audit evidence traceability, log exclusions and data corrections.

**Preprocessing code/version, actual transformations, exclusions and missingness:** **NOT YET IMPLEMENTED OR MEASURED**.

## 5. Uses

**Appropriate proposed uses:** Research on maturity scoring, inter-rater reliability, gap-detection benchmarks, evaluation of human-in-the-loop decision support and documented subgroup performance.

**Inappropriate uses:** Public ranking or naming of organizations; automated legal or ISO certification; sanctions; commercial profiling; use beyond consent; training unrelated models on confidential records; extrapolation to all Peruvian organizations without representative sampling.

**Known limitations:** Self-reporting bias; differences in documentary practices; sector/size imbalance; possible regulatory changes; limited access to high-quality ground truth; expert disagreement.

**Evaluation protocol (planned):** Organization-disjoint development/validation/test partitions, with a documented random seed and held-out final test. If sample size is small, use appropriate grouped cross-validation while protecting final confirmatory evaluation.

## 6. Distribution

**Current availability:** NOT RELEASED; no public download URL or license. Access arrangements **TO BE DEFINED** after consent, data-protection and institutional review.

**Proposed access tiers:** (a) Restricted raw evidence for authorized assessors, (b) de-identified derived research tables subject to disclosure-risk review, (c) synthetic/public examples and metadata for reproducibility.

**Redistribution rights, license, DOI, hosting and permitted users:** **UNKNOWN — TO INVESTIGATE**. Do not publish proprietary documents or personal data by default.

## 7. Maintenance

**Stewardship:** Dataset owner, access administrator and contact point **TO BE DESIGNATED**.

**Versioning:** Record schema version, assessment rubric version, legal/standards reference version, collection dates, label corrections and release changelog.

**Updates:** Periodic review of legal references and governance controls; explicit procedures for corrections, withdrawals, retention periods, access revocation and secure deletion.

**Monitoring:** Assess distribution drift by sector and size, annotation consistency, missing evidence and changing legal requirements.

**Retention schedule, budget, maintenance contact and deprecation plan:** **UNKNOWN — TO INVESTIGATE**.

---

## Readiness gaps before a defensible empirical submission

- Obtain organizational participation and approvals; document lawful data collection.
- Define maturity rubric, dataset schema, expert labeling and quality-control protocol.
- Establish sample size and subgroup coverage; lock data partitions and evaluation metrics.
- Record preprocessing scripts and audit evidence to enable independent reproduction.
- Decide whether any dataset portion may be shared; otherwise provide a safe synthetic reproduction package.

**References for document structure:** Gebru et al. (2021), *Datasheets for Datasets*. Session 7 lecture materials, UNMSM.  
**Research-specific statements:** Proposed protocol, not completed data collection.
