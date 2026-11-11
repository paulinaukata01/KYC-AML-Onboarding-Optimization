# KYC & AML Corporate Onboarding Optimization

## 📌 Executive Summary
This repository contains a comprehensive **Business Requirements Document (BRD)** and **BPMN 2.0 Process Models** designed to optimize the Know Your Customer (KYC) and Anti-Money Laundering (AML) onboarding workflow for institutional banking clients. The proposed "To-Be" target state achieves a **35% reduction in onboarding cycle time** (from 14 to 9 business days) and improves auditability for regulatory compliance (GDPR, 5AMLD/6AMLD).

---

## 🎯 Key Objectives & Business Value
* **Cycle Time Reduction:** Streamlines corporate entity verification and Ultimate Beneficial Owner (UBO) discovery.
* **Automation & Risk Scoring:** Integrates an automated risk-tiering engine to categorize accounts (Low, Medium, High risk) upon document intake.
* **Auditability:** Replaces fragmented email communication with a centralized document intake portal featuring real-time status tracking.

---

## 📂 Repository Structure
```
kyc-aml-onboarding-optimization/
├── docs/
│   ├── Business_Requirements_Document_BRD.md
│   └── User_Stories_Acceptance_Criteria.md
├── diagrams/
│   ├── As_Is_Process_Flow.bpmn
│   └── To_Be_Process_Flow.bpmn
└── README.md
```

---

## 📝 Business Requirements (BRD Summary)

### Functional Requirements Matrix
| Req ID | Module | Feature Description | Priority |
| :--- | :--- | :--- | :--- |
| **FR-01** | Client Portal | Direct digital upload hub for identity docs, proof of address, and UBO registry files. | High |
| **FR-02** | Risk Engine | Automated risk calculation based on geographic risk, entity type, and PEP screening. | High |
| **FR-03** | Workflow | Automated task assignment routing high-risk/complex entities to Senior Compliance Specialists. | Medium |
| **FR-04** | SLA Tracker | Real-time operational reporting dashboard for pending onboarding pipelines. | Medium |

---

## 📊 Process Mapping Overview

* **As-Is Workflow:** Manual PDF collection via email, sequential identity verification, and high exception rate (40% document resubmissions).
* **To-Be Workflow:** Automated portal checklist validation, parallel API verification against sanction lists, and exception-only manual escalation.

---

## 🛠️ Tools & Methodologies Highlighted
* **Business Analysis:** Requirements Elicitation, Gap Analysis, Stakeholder Management, SLA Optimization.
* **Process Modeling:** BPMN 2.0 (Camunda, Lucidchart, Visio).
* **Domain Knowledge:** KYC/AML Compliance, Corporate Onboarding, Sanctions & PEP Screening.

---
*Created by [Paulina Ukata](https://www.linkedin.com/in/paulina-ukata-6281902b4/) for Business Analyst Portfolio.*
