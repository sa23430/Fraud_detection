# Fraud_detection

## Project Objective
Detect  fraudulent charges to enable early intervention, while minimizing customer engagement on non-fraudulent charges

## Data description
Transactions made by credit cards in September 2013 by European cardholders.Transactions that occurred in two days
Dimensions: 31 columns; ~280k rows
Unique features: Highly imbalanced data: 492 frauds out of 284,807 transactions (0.172% fraud)

## Metric selection
Recall as it measures the percentage of actual fraud that were correctly classified

## Results
Stacking ( 36 - Number of fraud charged not detected  || 22905 -  Number of false alarms to customers)

Random Forest ( 71 - Number of fraud charged not detected  || 472 -  Number of false alarms to customers)

Gradient Boosting ( 39 - Number of fraud charged not detected  || 948 -  Number of false alarms to customers)
