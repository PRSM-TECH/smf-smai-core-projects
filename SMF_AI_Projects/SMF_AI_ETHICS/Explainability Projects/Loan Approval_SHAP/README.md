# Explainability in Loan Approval AI using SHAP

## 📋 Project Overview

This project focuses on interpreting AI-driven loan approval decisions using SHAP (SHapley Additive exPlanations). The goal is to make model decisions transparent and trustworthy for both technical and non-technical stakeholders.

* **Model**: Random Forest Classifier
* **Explainability Technique**: SHAP TreeExplainer
* **Dataset**: 1000 synthetic loan applications
* **Accuracy**: \~85%

## 🔍 Key Objectives

* Provide global feature importance insights
* Offer per-instance local explanations
* Improve transparency and user trust

## 🛠 Techniques Used

* **Model**: `RandomForestClassifier()`
* **Explanation Tool**: `shap.Explainer()`
* **Global Plot**: `shap.plots.bar()`
* **Local Plot**: `shap.plots.waterfall()`

## 📊 Results Summary

* **Top Features**: Credit Score, Income
* **Fairness Insight**: Gender had minimal impact, promoting fair decision logic
* **Stakeholder Value**: Visual clarity on why a decision was made

## ⚠️ Challenges

* SHAP visualizations can be too technical for non-AI users
* Local SHAP values were unstable for borderline applicants

## ✅ Fixes

* Simplified charts with stakeholder-friendly tooltips
* Used multiple-instance averaging for clearer explanations

## 💡 Key Learnings

* SHAP improves AI decision transparency
* Helps bridge the gap between model accuracy and interpretability
* Supports SoulMindFusion principles by aligning clarity with correctness

## 📌 Next Steps

* Extend this project with LIME and PDP comparisons
* Build an end-user dashboard using SHAP visuals

---

This project is part of the **SoulMindFusion AI Ethics Portfolio** under the Explainability category.
