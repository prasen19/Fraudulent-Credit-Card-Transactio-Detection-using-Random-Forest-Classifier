# Fraudulent Credit Card Transaction Detection

![card](Credit_card.jpg)

## Overview
1. Credit card companies must be able to recognize fraudulent credit card transactions in order to provide safe banking to their customers.
2. The Dataset is highly imbalanced. So we must achieve high recall such that we should not miss any fraud transaction. 
3. This was one of the Kaggle competition and the dataset was made available on Kaggle.

## Dataset
The dataset can be downloaded [here](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle.

1. The dataset contains transactions made by credit cards in September 2013 by European cardholders.
2. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
3. The dataset is highly unbalanced, the positive class (frauds) accounts for 0.172% of all transactions.
4. It contains only numerical input variables which are the result of a PCA transformation.
5. Unfortunately, due to confidentiality issues, they cannot provide the original features and more background information about the data.
6. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.
7. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
8. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning.
9. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
