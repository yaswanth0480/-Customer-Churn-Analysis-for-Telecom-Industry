# Telecom Customer Churn Analysis

## 📌 Project Overview
End-to-end workflow for predicting and analyzing telecom customer churn:
- SQL-based feature aggregation
- Machine learning models (Logistic Regression & Random Forest)
- Model evaluation (confusion matrices, ROC curves, metrics)
- Customer segmentation (At Risk, Loyal, Dormant, Neutral)
- Automated reporting with PowerPoint
---
## 📊 Key Outputs
- Confusion Matrices & ROC Curves  
- Feature Distributions  
- Segmentation Results (`customer_segments_test.csv`)  
- Final Report (`Telecom_Churn_Report.pptx`)  

---

## 🔎 Segmentation
- **At Risk** → High churn probability or frequent complaints + low recharge  
- **Loyal** → Low churn probability, consistent recharge, high usage  
- **Dormant** → Low activity and recharge frequency  
- **Neutral** → Remaining customers  

---

## 📈 Recommendations
- Resolve complaints quickly for high-risk customers  
- Offer personalized recharge bundles for low-frequency users  
- Provide loyalty rewards for long-tenure customers  
- Run win-back campaigns for dormant users  

---

## 🛠️ Dependencies
- Python 3.9+
- scikit-learn  
- pandas  
- seaborn  
- eli5  
- python-pptx  
- sqlalchemy  

---

## 📌 Note
- SHAP summary plots are excluded for simplicity.  
- All outputs are reproducible by running the notebook end-to-end.  
