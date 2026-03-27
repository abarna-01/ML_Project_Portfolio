{\rtf1\ansi\ansicpg1252\cocoartf2865
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Loan Default Prediction using Machine Learning\
\
## \uc0\u55357 \u56524  Problem Statement\
Predict whether a customer will default on a loan to help financial institutions minimize risk.\
\
---\
\
## \uc0\u55357 \u56522  Dataset\
- Source: Kaggle Credit Risk Dataset  \
- Features include income, employment, loan details, and credit history  \
\
---\
\
## \uc0\u9881 \u65039  Approach\
\
### 1. Data Preprocessing\
- Missing value imputation (median)\
- One-hot encoding for categorical variables\
- Label encoding for ordinal features\
- Feature scaling using StandardScaler\
\
### 2. Models Used\
- Logistic Regression\
- K-Nearest Neighbors (KNN)\
- Support Vector Machine (SVM)\
\
### 3. Evaluation Metrics\
- Recall (primary metric)\
- Precision\
- ROC-AUC\
\
---\
\
## \uc0\u55357 \u56960  Key Results\
\
- Logistic Regression with threshold tuning improved recall from ~52% to ~71%\
- KNN showed high precision but lower recall\
- SVM achieved higher AUC but slightly lower recall than Logistic Regression\
\
---\
\
## \uc0\u9989  Final Model\
\
**Logistic Regression with threshold tuning**\
\
Chosen for its ability to maximize recall and identify high-risk applicants.\
\
---\
\
## \uc0\u55357 \u56481  Business Impact\
\
- Enables early identification of high-risk customers  \
- Helps reduce financial losses due to loan defaults  \
- Supports data-driven decision making  \
\
---\
\
## \uc0\u55357 \u56524  Conclusion\
\
The model improves risk detection by focusing on recall, ensuring better identification of defaulters while maintaining practical usability.\
\
---\
\
## \uc0\u55357 \u57056 \u65039  Tech Stack\
\
- Python\
- Pandas, NumPy\
- Scikit-learn\
- Matplotlib, Seaborn}