# Telecom-Customer-Churning-Risk-Prediction

# Data File Information

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The data set includes information about:

Customers who left within the last month – Churn

Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and streaming movies

Customer account information – how long they’ve been a customer (tenure), contract, payment method, paperless billing, monthly charges, and total charges

Demographic info about customers – gender, age (senior citizen or not), and if they have partners and dependents

# Goal
1. Data Analytics to understand the patterns.
2. Predict Churning.
3. Provide an evaluation of how the model performs.
4. Segment the customers to understand similar behaviour.
5. Identify churn drivers

# Data Analytics
1. Overall data properties
2. Descriptive Statistics
3. Understand individual categories in each feature
4. Uni-variate analysis (Individual feature behaviour)
5. Bi-variate analysis (Individual relationship with Churn attribue and relationship between independent attributes)
6. Multi-variate analysis (Correlation analysis)
7. Statistical Analysis: Hypothesis Testing
8. Customer Segmentation analysis

# Data Transformations
1. Removed unwanted features
2. Removed null values
3. Corrected data types
4. Created new feature
5. Binary encoding
6. One-Hot encoding
7. Data scaling
8. Sampling (optional)

# Performance Metrics (Success Criteria)
1. Metrics utilised: Recall, Precision, F1-Score, Accuracy
2. Most important metrics to consider: Recall of Predicted class (Its the true positive rate (TPR), the percentage of data samples that a machine learning model correctly identifies as belonging to a class of interest—the “positive class”—out of the total samples for that class)
3. A minimum of 75% churned customers should be predicted
4. Human evaluation on feature importances derived by Models with comparing to information extracted from the analysis

# Tool Version
1. Pandas: 1.2.4
2. Numpy: 1.22.0
3. SeaBorn: 0.11.1
4. Matplotlib: 3.6.0
5. Xgboost: 2.0.1
6. Sklearn: 1.2.2
7. imblearn: 0.12.2
8. scipy: 1.10.1
9. Jupyter Notebbok: 4.7.1
