# CREDIT-CARD-DEFAULT-PREDICTION
## Problem Statement and Data Summary ##

This project is aimed at predicting the case of customers' default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients


## Approach ##

1) Developed a binary classification model using algorithms such as Logistic Regression, SVC and XGBoost to predict whether a customer will default on credit card payments.
2)  Engineered a new class of attributes known as decayed field variables and developed out-of-pattern variables on historical credit and bureau data to identify risky customers and reduced default rate from 8.3% to 6.5%.
3)  Performed missing value imputation using KNN-Imputer, implemented SMOTE boosting to oversample the minority class observations and carried out hyperparameter tuning using Bayesian optimization.
4) Obtained Model Reason Codes ( MRCs ) by leveraging the concept of SHAP plots to cater to customer grievances and analyzed the Gains table to decide rejection cutoff.

## Result ##
We built a classification model that predicts the Potential credit card defaults for company risk management 

