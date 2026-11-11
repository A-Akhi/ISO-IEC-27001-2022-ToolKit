# ISO/IEC 27001:2022 Implementation & Operational Resilience Toolkit

[![Standard](https://img.shields.io/badge/Standard-ISO%2FIEC%2027001%3A2022-blue.svg)](https://www.iso.org/standard/27001)
[![Focus](https://img.shields.io/badge/Focus-ISMS%20%7C%20GRC%20%7C%20Incident%20Governance-darkgreen.svg)](#focus-areas)
[![Regulations](https://img.shields.io/badge/Alignment-DORA%20%7C%20NIS2%20%7C%20GDPR-orange.svg)](#regulatory-crosswalks)

A structured reference architecture, study synthesis, and operational template library for designing, implementing, and governing an **Information Security Management System (ISMS)** aligned with **ISO/IEC 27001:2022**.

This repository bridges enterprise IT Service Management (ITSM) and Major Incident Governance with cybersecurity risk management, operational resilience, and European regulatory compliance (DORA / NIS2).

---

## 📌 Repository Architecture

```text
├── 01-governance-clauses/        # Mandatory Management System (Clauses 4–10)
│   ├── clause-04-context.md      # Context, interested parties & ISMS scoping
│   ├── clause-05-leadership.md   # Security policy baseline & RACI matrix
│   ├── clause-06-planning.md     # Risk assessment methodology & objectives
│   ├── clause-07-support.md      # Competence, awareness & documented info
│   ├── clause-08-operation.md    # Risk treatment execution & operational control
│   ├── clause-09-evaluation.md   # Internal audit framework & management review
│   └── clause-10-improvement.md  # Nonconformity & corrective action playbooks
├── 02-annex-a-control-matrices/  # The 93 Controls (4 Themes)
│   ├── a5-organizational.md      # 37 controls (incidents, suppliers, policies)
│   ├── a6-people.md              # 8 controls (remote work, screening, NDAs)
│   ├── a7-physical.md            # 14 controls (perimeters, secure disposal)
│   ├── a8-technological.md       # 34 controls (access, DLP, configuration, monitoring)
│   └── statement-of-applicability.md # SoA mapping template with inclusion justifications
├── 03-incident-and-resilience/   # Operational Playbooks (A.5.24 - A.5.30)
│   ├── csirp-framework.md        # Computer Security Incident Response Plan
│   ├── supplier-risk-matrix.md   # Third-Party Risk Management (TPRM) checklist
│   └── continuity-testing.md     # ICT readiness & disaster recovery scenarios
└── 04-regulatory-mappings/       # EU Cross-Framework Alignment
    ├── dora-crosswalk.md         # ICT Incident reporting & resilience controls
    └── nis2-crosswalk.md         # Supply chain security & 24h notification rules
```
---
## 🎯 Core Focus Areas
1. Mandatory Clauses (PDCA Lifecycle)

    a) Plan (Clauses 4–7): Establishing organizational scope, leadership oversight, quantitative/qualitative risk assessment methodologies, and        resource allocation.
    b) Do (Clause 8): Operationalizing risk treatment plans and control baselines.
    c) Check (Clause 9): Performance monitoring, conducting internal audits, and facilitating formal executive management reviews.
    d) Act (Clause 10): Remediation management, root-cause analysis (RCA), and continuous service improvement.

2. Annex A: 2022 Control Themes

Comprehensive mapping of all 93 controls categorized under the consolidated 4-theme structure:
    a) Organizational Controls (A.5): Special focus on A.5.19–A.5.23 (Supplier Governance) and A.5.24–A.5.28 (Incident Management).
    b) People Controls (A.6): Lifecycle security from onboarding to termination.
    c) Physical Controls (A.7): Perimeter protection and operational environment security.
    d) Technological Controls (A.8): Focus on new 2022 controls: Threat Intelligence (A.5.7), Cloud Security (A.5.23), Data Leakage Prevention         (A.8.12), Configuration Management (A.8.9), and Monitoring (A.8.16).

3. Incident Governance & Operational Resilience

Incident Escalation Taxonomies: Severity classification matrices mapping ITSM P1/Major Incident workflows to security breach severity levels.

Timeline Compliance: Operational playbooks designed to meet European statutory reporting triggers (e.g., DORA 4h/24h milestones, NIS2 early warnings).




