Hi,

In this repository, I applied Machine Learning Algorithms to Telco Customer Churn dataset which can be reached from www.kaggle.com/blastchar/telco-customer-churn .

In Exploratory Data Analysis, it can be figured out that;
  
  1) Senior citizen customers have significant churn rate.
  2) Churn mostly happened with less tenure.
  3) Churn rate is much higher in fiber optic internet service users.
  4) Customers who have month to month contract have higher churn rate.
  5) Customers who use electronic check as payment method have high churn rate.

These insights can be useful for further decisions and campaigns.

In the dataset, Churn column is the most important column for classification. Churn column is imbalanced. So that, I created two notebooks that one of them is created with using smote technic.
  
  - SMOTE is an oversampling technique where the synthetic samples are generated for the minority class.
 
I used 7 machine learning algorithms and applied hyperparameter tuning by RandomizedSearchCV. XGBoostClassifier got the highest F1 score when I applied smote technic.
