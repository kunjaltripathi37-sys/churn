# churn
This project builds a machine learning model to predict customer churn, enabling businesses to proactively retain customers. It covers the complete ML pipeline from data preprocessing to model evaluation and business insights.

Dataset Description

The dataset includes:

Demographics: Gender, Age
Customer Behavior: Tenure, ContractType
Services Used: InternetService, TechSupport
Billing Information: MonthlyCharges, TotalCharges
Target Variable: Churn (Yes/


 Encoding
Binary encoding using .map():
Gender
TechSupport
Churn
One-hot encoding using pd.get_dummies():
ContractType
InternetService
Feature Scaling
Applied StandardScaler for normalization
Ensures features contribute equally to the model

Model Building
Logistic Regression
Used as a baseline model
Chosen for:
Interpretability
Simplicity
Strong performance on structured data

Results
ROC-AUC Score: ~0.98
Recall (Churn Class): High (critical for business)
Model effectively identifies high-risk customer
