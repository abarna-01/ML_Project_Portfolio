# Customer Churn Prediction using Machine Learning

## Project Overview
Customer churn is a major challenge for telecom companies because losing customers directly impacts revenue. Retaining existing customers is significantly cheaper than acquiring new ones.

This project builds a machine learning model to predict whether a customer is likely to churn based on demographic information, subscription details, and billing data.

The objective is to help telecom companies identify customers at risk of leaving and implement retention strategies.

---

## Dataset
The Telco Customer Churn dataset contains information about 7043 telecom customers including:

- Demographics
- Service subscriptions
- Billing information
- Contract details
- Customer tenure

Target variable:

Churn (Yes / No)

---

## Machine Learning Workflow

1. Exploratory Data Analysis
2. Data preprocessing
3. Feature encoding
4. Train-test split
5. Model training
6. Model evaluation
7. Handling class imbalance
8. Threshold tuning
9. Feature importance analysis
10. Business insights and recommendations

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Precision-Recall Curve

---

## Best Model

Logistic Regression with class weighting and threshold tuning.

Performance:

Recall ≈ 0.88  
ROC-AUC ≈ 0.83

This ensures that most customers likely to churn are correctly identified.

---

## Key Drivers of Churn

Factors increasing churn probability:

- Fiber optic internet service
- Paperless billing
- Electronic check payment method
- Month-to-month contracts

Factors reducing churn probability:

- Long-term contracts
- Technical support services
- Online security services
- Higher customer tenure

---

## Business Recommendations

1. Encourage long-term contracts through loyalty incentives.
2. Improve customer experience for fiber optic internet users.
3. Promote value-added services such as technical support and security packages.
4. Identify high-risk customers and run targeted retention campaigns.

---

## Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Google Colab
