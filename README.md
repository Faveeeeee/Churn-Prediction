# Customer Churn Prediction

This project predicts whether a bank customer will churn (exit) or stay, using a real-world dataset. The business challenge is clear: customer attrition is expensive, and banks must anticipate which clients are at risk to act before it’s too late.

## Key Steps

## EDA: 
Found that churn was higher among older customers, inactive members, customers in Germany, and those with higher balances.

## Preprocessing: 
One-hot encoding for categorical features, scaling numerical features, and handling imbalance with class weights.

## Models Compared: 
Logistic Regression, and XGBoost.

## Results

## Best Model: 
Logistic Regression with class weights.

## Performance (Test Set):

Recall (Churned Customers): 0.73

Precision (Churned Customers): 0.39

Accuracy: 72%

 Logistic Regression gave the best recall–precision trade-off, crucial for retaining at-risk customers.

## Business Insights

Inactive members are most likely to churn → re-engagement programs are critical.

Geography matters: churn is highest in Germany.

Older, high-balance customers are at greater risk and need retention strategies.

Female customers show higher churn, requiring tailored engagement.

## Future Work

Ensemble models & threshold tuning for higher recall.

Advanced feature engineering (interactions, trends).

Validation on more recent datasets.
