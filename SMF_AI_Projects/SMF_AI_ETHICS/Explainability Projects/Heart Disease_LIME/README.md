# Explainability in Healthcare AI using LIME

## 📋 Project Overview

This project applies LIME (Local Interpretable Model-agnostic Explanations) to interpret predictions made by a Random Forest classifier trained on health-related data (breast cancer dataset used as a proxy for heart disease classification).

* **Model**: Random Forest Classifier
* **Explainability Technique**: LIME
* **Dataset**: Breast cancer dataset (30 features)
* **Accuracy**: \~96%

## 🔍 Key Objectives

* Offer clear, patient-level prediction insights
* Assist healthcare professionals in understanding AI risk assessments

## 🛠 Techniques Used

* **Model**: `RandomForestClassifier()`
* **Explanation Tool**: `LimeTabularExplainer()`
* **Local Explanation**: `explain_instance()` and `show_in_notebook()`

## 📊 Results Summary

* Top 5 predictive features highlighted per patient
* Visual support for each prediction improves human trust and decision review

## ⚠️ Challenges

* LIME’s randomness led to variable output
* Long and complex feature names were hard to interpret

## ✅ Fixes

* Set a consistent random state for reproducibility
* Preprocessed feature names for readability

## 💡 Key Learnings

* LIME builds local surrogate models for every prediction
* Essential for transparency in sensitive fields like healthcare
* Promotes SoulMindFusion's mission of explainable, ethical AI

## 📌 Next Steps

* Cross-compare with SHAP and PDP methods
* Design clinician-facing dashboards with multi-patient visuals

---

This project contributes to the **SoulMindFusion Explainability Framework**.
