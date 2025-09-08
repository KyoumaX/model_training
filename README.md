# Logistic Regression & Random Forest Classifier
1. Obtained the "Telco customer churn" dataset from Kaggle
2. Performed cleaning, header standardization, data type adjustment, scaling (for numeric fields) and encoding (for categoric fields)
3. Built and trained a LogisticRegression model with L1-Regularization on processed dataset, and performed grid search to obtain best value of regularization coefficient
4. Performed 5-fold cross validation and obtained ~78% accuracy for the LogisticRegrression model
5. Built and trained a RandomForestClassifier with 100 estimators, obtaining ~78% prediction accuracy on 5-fold cross validation
6. Identified contract_Month-to-Month as the feature with highest Gini Importance
