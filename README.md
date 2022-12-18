# Telecommunication Customer Churn Prediction
This project aims to identify factors that determine customer churn status and develop
a framework to automatically predict customer churn based on machine learning
algorithms.

The dataset contains information about 7043 customers from a fictional telecommunication
(telco) company in Q3 in California. 
The data is provided by IBM Cognos Analytics. \
(dataset on Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customerchurn)

I have conducted Exploratory Data Analysis with visualization plots, data cleaning, categorical variable one-hot-encoding, 
and feature scaling (normalizing numerical features). In addition, I also addressed the multicollinearity via feature selection 
and imbalanced data issue via ADASYN oversampling. I experimented with SVM, Logistic Regression, and Random Forest machine learning models
to predict customer churn status (1: churned, 0: non-churned). SVM achieved 80.03% accurcay and 91.26% true negative rate on test set.

The Python Notebook is provided in 'Telco_Customer_Churn.ipynb'. 
