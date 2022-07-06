## Customer Churn Modelling - Goal is to predict if a bank’s customer will stay or leave the bank

Using a source of 10,000 bank records, machine learning models were applied to predict the likelihood of customer churn. The following steps were used:

## Clean the data

Removal of unnecessary data fields including individual customer IDs and names. This helped in reducing dimensionality of data and list of columns left were Credit Score, Geography, Gender, Age, Length of time as a Bank customer, Balance, Number Of Bank Products Used, Has a Credit Card, Is an Active Member, Estimated Salary and Exited. Outliers present in the data were removed using z-score statistics.

Data set was standardized using standard scaler to bring all the features within similar range.


## Machine Learning using 4 different models

Tested seven different machine learning models to predict customer churn, including Support Vector Machine, Random Forest, XGBoost and LGBM. 

Used own random data to predict the output

<img src="https://github.com/shub-coder/Customer-Churn-Predictor/blob/main/prediction.png" width="550" height="300"/> 
