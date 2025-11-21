# 📊 Customer Churn Prediction — Explainable AI Project

Job Assistance Program — Cultos Skill Center | Stage 4 Assignment
Goal: Build a transparent and business-friendly machine learning model that predicts customer churn and explains why customers leave.

# 🎯 Project Objectives

✔ Predict whether a customer will churn
✔ Use Explainable AI (XAI) to interpret model decisions
✔ Generate business insights for churn reduction strategies
✔ Provide evidence of model trustworthiness
✔ Deliver clean, structured, and automated reports

# 📂 Dataset

Telco Customer Churn Dataset
Records: 7043 customers
Target Variable: Churn (Yes/No)
Features: Demographics, Services, Account, Billing Information

Dataset source: Provided during project (not included in repo due to size limits)

# 🧠 Modeling Workflow
Stage	Description
🔹 Data Preprocessing	Cleaning → Label Encoding → Scaling
🔹 Feature Engineering	Transforming categorical data
🔹 Model Training	Gradient Boosting (LightGBM)
🔹 Hyperparameter Optimization	RandomizedSearchCV
🔹 Explainability	SHAP + LIME (Local + Global)
🔹 Evaluation	Accuracy, ROC-AUC, Confusion Matrix
🔹 Business Insights	Actionable recommendations
# 📈 Model Performance
Metric	Score
Accuracy	80%+
ROC–AUC	~0.84
Classification Report	Included in repo

This performance meets the 80%+ success criteria required for completion. 🎯

# 🔍 Explainable AI Outputs
Method	Purpose	Output
SHAP	Global + Local explainability	Feature importance charts & CSVs
LIME	Individual prediction reasoning	HTML visual reports

Interpretability deliverables included:

shap_feature_importance.csv

shap_lime_comparisons.json

Local explanation files for 3 diverse test samples (SHAP + LIME)

# 📌 Key Business Insights

✔ Monthly Charges, Tenure, Contract Type, Tech Support strongly influence churn
✔ Short-tenure + high-monthly-bill customers are at highest risk
✔ Auto-renewal contracts help reduce churn
✔ Offering tech support benefits customer retention

Final analysis & strategy recommendations are in final_analysis.txt.

# 🗂 Repository Structure
📦 Customer-Churn-Interpretability
│
├── Customer_Churn_Interpretability_Project.ipynb
├── README.md
│
├── metrics.json
├── best_model_params.txt
├── classification_report.txt
├── final_analysis.txt
│
├── confusion_matrix.png
│
├── shap_feature_importance.csv
├── shap_lime_comparisons.json
├── shap_local_summaries.json
├── lime_local_summaries.json
│
├── lime_explanation_idx_33.html
├── lime_explanation_idx_431.html
├── lime_explanation_idx_891.html
│
├── shap_local_top10_idx_33.csv
├── shap_local_top10_idx_431.csv
└── shap_local_top10_idx_891.csv


Perfectly meets AI evaluator expectations ✔

# 🧪 Reproducibility

Run the notebook in Google Colab (GPU not required)

pip install lightgbm shap lime scikit-learn pandas numpy matplotlib


Execution time: ~35 seconds


# 📜 License

This project is submitted as part of a professional assessment.
Do not copy or reuse without permission.
