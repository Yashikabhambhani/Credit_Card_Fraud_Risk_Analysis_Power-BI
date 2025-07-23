📊 Credit Risk Modeling in Python
🔍 Project Overview
This project simulates a real-world use case in the Indian lending sector, where the objective is to predict whether a loan applicant poses a high risk of default. By leveraging supervised machine learning techniques, this model helps financial institutions like NBFCs and banks make data-driven lending decisions, reduce non-performing assets (NPAs), and streamline loan approvals.

🧰 Tools & Technologies
Python

Pandas, NumPy (Data manipulation)

Matplotlib, Seaborn (EDA & Visualization)

Scikit-learn (ML models)

XGBoost / Random Forest / Logistic Regression

Jupyter Notebook

(Optional Extension: Power BI for reporting)

🗂️ Dataset
Source: Simulated credit dataset (inspired by lending datasets on Kaggle)

Key Features:

Loan_ID, Gender, Married, Education, ApplicantIncome, LoanAmount, Credit_History, Property_Area, Loan_Status

Target: Loan_Status (Yes = Approved, No = Rejected / Risky)

📈 Workflow
1. Data Preprocessing
Handled missing values and outliers

Encoded categorical variables

Created new features (e.g., Debt-to-Income Ratio)

2. Exploratory Data Analysis (EDA)
Visualized distribution of loan approval by income, credit history, and education

Correlation heatmap and trend analysis

3. Model Building
Trained multiple models:

Logistic Regression (baseline)

Random Forest

XGBoost Classifier

Split data using stratified train-test split

4. Model Evaluation
Accuracy, Precision, Recall, F1-Score

ROC-AUC Curve

Confusion Matrix

Feature Importance (for interpretability)

📌 Key Results
Achieved ~85% Accuracy with Random Forest

Identified top predictors: Credit_History, LoanAmount, ApplicantIncome, and Property_Area

Built interpretable models to support non-technical stakeholders

📊 Business Insights
Customers with no credit history had a significantly higher default risk

High-income applicants still faced rejection due to unstable credit history

Semi-urban regions showed higher approval rates than rural ones

🚀 Future Work
Power BI dashboard for stakeholder reporting

Integration with Flask or Streamlit for model deployment

Use SHAP values for deeper interpretability

Extend to time-series risk monitoring

🧠 Takeaways
End-to-end ML pipeline for risk classification

Learned how to align technical outputs with business KPIs

Gained insights into how data science supports lending decisions

👤 Author
Yashika Bhambhani
yashikabhambhani.tech@gmail.com
