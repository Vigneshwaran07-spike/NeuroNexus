# NeuroNexus: Credit Card Fraud Detection

This repository contains my solution for the **Credit Card Fraud Detection** task as part of the **NeuroNexus Innovations** internship. The objective was to build a machine learning model capable of detecting fraudulent transactions with a focus on handling class imbalance and evaluating the model with suitable metrics.

---

## 🔍 Overview

- **Dataset**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Transactions**: 284,807  
- **Fraudulent Transactions**: ~0.17%  

---

## ⚙️ Approach

- **Preprocessing**:
  - Normalized `Time` and `Amount` features using `StandardScaler`.
- **Handling Imbalance**:
  - Applied **SMOTE** (Synthetic Minority Oversampling Technique) to oversample the fraud class.
- **Model**:
  - Used **XGBoost Classifier** for high performance on imbalanced data.
- **Evaluation**:
  - Precision, Recall, F1-Score, AUPRC (Area Under Precision-Recall Curve).
- **Visualizations**:
  - Confusion Matrix
  - Precision-Recall Curve
  - Feature Importance Plot

---

## 📊 Results

| Metric      | Fraud Class Value |
|-------------|-------------------|
| Precision   | ~0.95             |
| Recall      | ~0.90             |
| F1-Score    | ~0.92             |
| AUPRC       | ~0.92             |

> 📈 Visual outputs:  
> - `confusion_matrix.png`  
> - `precision_recall_curve.png`  
> - `feature_importance.png`

---



