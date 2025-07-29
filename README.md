# 🛍️ E-commerce Shopper Behavior Prediction

This project predicts whether a user will make a purchase based on session-level behavioral data. It was built as part of a competition and addresses challenges such as class imbalance and noisy features. The model was evaluated using **Mean F1 Score**, with a final score of **0.64555**.

---

## 📌 Summary

- **Task**: Binary classification — `Made_Purchase: True/False`
- **Dataset**: User session data (one row per user)
- **Challenge**: Imbalanced data + potential label noise
- **Metric**: Mean F1 Score
- **Final Score**: 0.64555

---

## ⚙️ Techniques Used

- Data cleaning and preprocessing
- Handled imbalance using:
  - **SMOTE** (Synthetic Minority Over-sampling Technique)
  - **TomekLinks** undersampling
- Trained and evaluated multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Performed feature scaling and model evaluation using stratified train-test split

---

## 🚀 Planned Improvements

- Add cross-validation and hyperparameter tuning
- Include EDA with feature importance visualization
- Experiment with ensemble models (stacking/blending)
