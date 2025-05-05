# Governance Audit for Hiring Bias AI (EU AI Act Compliance)

## 📋 Project Overview

This project simulates an AI Governance Audit under the EU AI Act for a high-risk system: a Gender Bias Detection Model used in hiring.

* **System**: Resume Shortlisting AI
* **Developer**: SoulMindFusion Ethical AI Lab
* **Governance Objective**: Evaluate compliance with 9 key governance checks
* **Output**: Audit Score, Grade, JSON Log, and Governance Summary

## 🔍 Key Governance Checks

* High-Risk Classification ✔️
* Sensitive Data Usage ✔️
* Bias Detection & Mitigation ✔️
* Explainability Provided ✔️
* Performance Metrics Documented ✔️
* Audit Trail Available ✔️

## ✅ Results

* **Score**: 9/9
* **Governance Grade**: A+ (Fully Compliant)
* **Fairness Metric**: Demographic Parity (DPD = 0.6)
* **Accuracy**: 90%
* **Explainability Tool**: SHAP

## ⚙️ Tools Used

* Python (for checklist logic + audit summary)
* JSON export for audit logs

## 🧠 Challenges & Fixes

* Stakeholder trust issues → Added fairness logs + visual SHAP proofs
* Gender bias risks → Mitigated using Fairlearn (Exponentiated Gradient)

## 💡 Key Learnings

* Governance scoring improves model accountability
* Alignment with EU AI Act ensures ethical readiness
* SoulMindFusion principles of clarity + fairness fully upheld

## 📁 Outputs

* `audit_summary.json`
* Governance Report (case study)
* README.md (GitHub-ready)

## 📌 Next Steps

* Apply governance scoring to other projects (Explainability, Healthcare)
* Integrate with GDPR & Responsible AI frameworks
