# Telecom Churn Prediction Model (AUC 0.857) 🚀

Production-ready logistic regression model identifies customers with 95% churn risk. Built end-to-end: EDA → Feature Engineering → Model → Business Insights.

Open In Colab: https://colab.research.google.com/assets/colab-badge.svg)](telecom_churn_model.ipynb)

# 📈 Key Results(Metrics and Score)
AUC:0.857
Accuracy:87%
Churn Precision: 69%
Churn Recall: 25%

# 🎯 Business Impact
- Identifies "troubled customers": No contract renewal + high service calls = 95% churn probability
- Top 10 customers flagged with 76-95% risk scores
- 69% precision: Catch 25% of churners with minimal false alarms

# 🔍 Top Predictors (Feature Importance)
1. ContractRenewal (-2.35) ← No renewal = 4x churn risk
2. CustServCalls (1.48) ← 6+ calls = red flag
3. DataPlan (-1.06) ← Protective effect
4. HighCalls (0.78) ← Engineered feature

# 🛠️ Technical Highlights
- Feature Engineering: Renewal_Calls, HighCalls interactions (+6% AUC boost)
- 16 engineered features from 10 raw variables
- Production outputs: CSVs + charts ready for stakeholder review

# 📊 Outputs Included
logreg_coefficients.csv - All 16 feature coefficients
top_churn_risks.csv - Top 10 highest-risk customers (95% probability)
model_results.png - Confusion matrix + probability distribution

# 🎓 Dataset  
Dataset Source: https://www.kaggle.com/datasets/barun2104/telecom-churn  
3,333 customers | 11 features | 14.5% churn rate

# Summary
Target Customer #192 first (95% churn risk, no renewal, 298 DayMins). Model catches 25% of churners at 69% precision. Ready for production retention campaigns.

# 📝 Run Locally
bash
pip install -r requirements.txt
python telecom_churn_model.py



