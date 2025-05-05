# Gender Bias in Job Hiring AI

## 📋 Project Overview
This project focuses on detecting and mitigating gender bias in AI-driven hiring decisions. The model initially favored male applicants, and fairness was improved using bias mitigation techniques.

- **Model**: Logistic Regression
- **Fairness Metric**: Demographic Parity Difference (DPD)
- **Dataset**: 1000 synthetic resumes
- **Bias Mitigation**: Exponentiated Gradient (Fairlearn)

## 📊 Key Results
- **Before Bias Fix**: DPD = 0.8 | Accuracy = 100%
- **After Bias Fix**: DPD = 0.6 | Accuracy = 90%

## 🛠 Techniques Used
- Model: `LogisticRegression()`
- Bias Fix: `ExponentiatedGradient()`
- Bias Metric: `demographic_parity_difference()`
- Accuracy: `accuracy_score()`

## ⚠️ Challenges
- SettingWithCopyWarning during encoding
- Over-compensation towards females initially
- Ethical review for borderline cases

## ✅ Fixes
- Used `.loc` for encoding
- Tuned fairness constraints
- Manual review for SMF alignment

## 🧠 Key Learnings
- Fairness is more than numbers – ethical intent matters.
- SMF principles guided deeper fairness evaluation.
