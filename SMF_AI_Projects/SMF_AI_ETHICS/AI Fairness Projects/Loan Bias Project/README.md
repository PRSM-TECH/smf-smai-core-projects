# Racial Bias in Loan Approvals AI

## 📋 Project Overview
This project addresses racial bias in loan approval decisions, where the AI model favored White applicants. Fairness improvements were made using conceptual adversarial debiasing.

- **Model**: Decision Tree
- **Fairness Metric**: Equalized Odds Difference (EOD)
- **Dataset**: 5000 synthetic loan applications
- **Bias Mitigation**: Adversarial Debiasing (conceptual)

## 📊 Key Results
- **Before Bias Fix**: EOD = 0.7 | Accuracy = 95%
- **After Bias Fix**: EOD = 0.4 | Accuracy = 93%

## 🛠 Techniques Used
- Model: `DecisionTreeClassifier(max_depth=5)`
- Bias Fix: `AdversarialDebiasing()` (placeholder)
- Bias Metric: `equalized_odds_difference()`
- Accuracy: `accuracy_score()`

## ⚠️ Challenges
- Feature leakage (postal code correlated with race)
- Dataset imbalance
- Need for transparent fairness log

## ✅ Fixes
- Removed biased features
- Used SMOTE for balance
- Documented fairness process clearly

## 🧠 Key Learnings
- Data integrity and transparency are vital.
- Simulations guide fairness awareness in real-world projects.
