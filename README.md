# Telecom Churn Prediction 🚀

Logistic Regression model predicting customer churn (AUC: 0.857)

Model Results: model_results.png

# 🎯 Business Problem
Predict which telecom customers will churn to prioritize retention offers.

## 📊 Key Results
| Metric | Value |
|--------|-------|
| **AUC Score** | **0.857** |
| **Accuracy** | 85.7% |
| **Precision (Churn)** | 69% |
| **Top Predictor** | No contract renewal (2.3x risk) |

## 💡 Actionable Insights
1. **95% churn risk profile**: No contract renewal + 6+ service calls
2. **Protective factor**: Data plan customers churn 40% less
3. **Top 10 risks flagged**: 76-95% churn probability customers ready for win-back

## 📁 Files
| File | Description |
|------|-------------|
| `telecom_churn_model.ipynb` | Complete pipeline (EDA → Model → Insights) |
| `logreg_coefficients.csv` | Feature importance rankings |
| `top_churn_risks.csv` | 10 highest risk customers |
| `model_results.png` | Confusion matrix + probability distribution |

## 🛠️ Tech Stack
Python | scikit-learn | pandas | matplotlib | seaborn


