# Telecom Customer Churn Analysis

## 📌 Project Overview
End-to-end workflow for predicting and analyzing telecom customer churn:
- SQL-based feature aggregation
- Machine learning models (Logistic Regression & Random Forest)
- Model evaluation (confusion matrices, ROC curves, metrics)
- Customer segmentation (At Risk, Loyal, Dormant, Neutral)
- Automated reporting with PowerPoint

---

## 📂 Repository Structure
├── Telecom_Churn_Analysis.ipynb   # Main Colab notebook ├── requirements.txt               # Python dependencies ├── README.md                      # Project documentation └── outputs/                       # Generated outputs ├── LogisticRegression_confusion_matrix.png ├── LogisticRegression_roc.png ├── RandomForest_confusion_matrix.png ├── RandomForest_roc.png ├── segmentation_counts.png ├── dist_avg_call_duration.png ├── dist_avg_recharge_freq.png ├── dist_avg_recharge_amount.png ├── dist_complaints_per_month.png ├── dist_low_value_recharge_ratio.png ├── churn_probability_rf.png ├── customer_segments_test.csv └── Telecom_Churn_Report.pptx

---

## ⚙️ Setup
```bash
git clone https://github.com/your-username/telecom-churn-analysis.git
cd telecom-churn-analysis
pip install -r requirements.txt
jupyter notebook Telecom_Churn_Analysis.ipynb
