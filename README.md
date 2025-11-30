# Customer-Churn-Prediction-model
A data-driven churn prediction model that identifies at-risk customers and highlights key factors behind churn.
📉 Customer Churn Prediction Model

Project Title: Customer Churn Prediction
Name: Mahenoor Ashraf
Internship Program: HEPro Business Analytics Internship
Duration: 2 Months
Domain: Machine Learning / Data Analytics
Mentor: HEPro Training Team

This project focuses on analyzing telecom customer churn and building predictive models to identify customers who are likely to leave the service. The system is built using end-to-end data preprocessing, exploratory analysis, machine learning models, and evaluation on real telecom churn data.

📌 Project Objective

The main goals of this project are to:

Understand customer churn behavior using Exploratory Data Analysis (EDA).

Identify the major factors influencing churn such as contract type, tenure, and payment method.

Build multiple machine learning models and compare their performance.

Develop a reliable churn prediction system to help businesses reduce customer loss.

Provide final insights and recommendations based on data-driven findings.

🗂️ Project Workflow
1️⃣ Dataset Understanding & Cleaning

Telecom Customer Churn Dataset

7,043 records, 21 features

Target variable: Churn (Yes/No → 1/0)

Cleaned TotalCharges, handled missing/incorrect values

Dropped irrelevant features (customerID)

Categorical variables Label Encoded

Applied SMOTE to fix class imbalance

🔍 Exploratory Data Analysis (EDA)
Univariate Analysis

Tenure: majority customers have short tenure

MonthlyCharges: higher charges correlate with churn

InternetService: Fiber Optic most common

Contract: month-to-month users dominate

PaymentMethod: Electronic check used by most churners

Bivariate Analysis

Low tenure → high churn

High monthly charges → higher churn

Fiber optic users → higher churn

Month-to-month contracts → maximum churn

Electronic check users → highest churn rate

Key Churn Drivers

Contract Type

Tenure

MonthlyCharges

PaymentMethod

InternetService

🤖 Model Development

Trained 8 machine learning models:

Logistic Regression

Naive Bayes

Decision Tree

Random Forest

AdaBoost

Gradient Boosting

XGBoost

LightGBM

Train–Test Split: 80:20
Class Imbalance: Handled using SMOTE
🧪 Model Evaluation

Metrics Used:
Accuracy, Precision, Recall, F1-Score, ROC-AUC

🔥 Top Performing Models
Model	Accuracy	Notes
Logistic Regression	81.83%	Best performing, interpretable
Gradient Boosting	81.05%	High precision, strong ROC-AUC
Random Forest	79.21%	Stable and robust
LightGBM	79.77%	Fast and efficient
🏆 Best Model: Logistic Regression

Chosen because:

Highest accuracy

Best balance of Precision, Recall, and F1

Highly interpretable for business decisions

Strong ROC-AUC score

📈 Final Insights
Customers most likely to churn:

Month-to-month contract users

High monthly charge customers

Fiber optic internet users

Electronic check payment users

Newer customers with tenure < 12 months

📝 Recommendations

Provide discounts for new customers (first 3–6 months)

Promote long-term contract plans

Improve fiber optic service experience

Encourage switching to auto-pay or secure payment options

Offer personalized retention plans to high-churn segments

🧩 Challenges & Solutions
Challenge	Solution
Incorrect data types	Cleaned & converted columns
Class imbalance	Used SMOTE oversampling
Overfitting	Compared multiple models
Identifying key churn drivers	Performed detailed EDA & feature importance analysis
Multiple categorical variables	Applied Label Encoding
🎯 Learnings & Takeaways

Complete end-to-end ML pipeline development

Advanced EDA (univariate + bivariate)

Feature engineering & encoding

Model comparison and performance evaluation

Handling imbalanced datasets

Understanding business impact through insights

📁 File Structure (Recommended)
customer-churn-prediction/
│
├── data/
│   └── telecom_churn.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── reports/
│   └── Customer_Churn_Project_Report.pdf
│
├── models/
│   └── final_model.pkl
│
├── images/
│   └── eda_plots.png
│   └── confusion_matrix.png
│
└── README.md

📎 References

Scikit-Learn Documentation

XGBoost Docs

LightGBM Docs

Kaggle Telecom Customer Churn Dataset

Seaborn & Matplotlib Guides
