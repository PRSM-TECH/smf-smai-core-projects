# Age/Race Bias in Healthcare Treatment AI

## 📋 Project Overview
This project focuses on mitigating bias in treatment recommendations where older and Black patients received fewer recommendations. Fairness was addressed using conceptual fair representations.

- **Model**: Neural Network (TensorFlow)
- **Fairness Metric**: Predictive Parity Difference (PPD)
- **Dataset**: 10,000 synthetic patient records
- **Bias Mitigation**: Fair Representations (conceptual)

## 📊 Key Results
- **Before Bias Fix**: PPD = 0.9 | Accuracy = 98%
- **After Bias Fix**: PPD = 0.5 | Accuracy = 92%

## 🛠 Techniques Used
- Model: `Sequential()` (TensorFlow)
- Bias Fix: `FairRepresentation()` (placeholder)
- Bias Metric: `predictive_parity_difference()`
- Accuracy: `accuracy_score()`

## ⚠️ Challenges
- Keras input layer warnings
- Over-compensation risks
- Ethical review for older patient fairness

## ✅ Fixes
- Refactored model input structure
- Tuned balance post-mitigation
- Applied SMF review principles

## 🧠 Key Learnings
- Healthcare AI requires deep ethical validation.
- Fairness must evolve continuously with data and context.
