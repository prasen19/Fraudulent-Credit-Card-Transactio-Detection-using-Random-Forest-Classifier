# Fraudulent Credit Card Transaction Detection

![card](Credit_card.jpg)

## Overview
1. Credit card companies must be able to recognize fraudulent credit card transactions in order to provide safe banking to their customers.
2. The Dataset is highly imbalanced. So we must achieve high recall such that we should not miss any fraudulent transaction. 
3. This was one of the Kaggle competitions and the dataset was made available on Kaggle.

## Imbalanced Classification

Classification predictive modeling involves predicting a class label for a given observation.

An imbalanced classification problem is an example of a classification problem where the distribution of examples across the known classes is biased or skewed. The distribution can vary from a slight bias to a severe imbalance where there is one example in the minority class for hundreds, thousands, or millions of examples in the majority class or classes.

Imbalanced classifications pose a challenge for predictive modeling as most of the machine learning algorithms used for classification were designed around the assumption of an equal number of examples for each class. This results in models that have poor predictive performance, specifically for the minority class. This is a problem because typically, the minority class is more important and therefore the problem is more sensitive to classification errors for the minority class than the majority class.

Please refer this [article](https://www.analyticsvidhya.com/blog/2021/06/5-techniques-to-handle-imbalanced-data-for-a-classification-problem/) for how to deal with imbalanced data.

## Dataset
The dataset can be downloaded from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

1. The dataset contains transactions made by credit cards in September 2013 by European cardholders.
2. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
3. The dataset is highly unbalanced, the positive class (frauds) accounts for 0.172% of all transactions.
4. It contains only numerical input variables which are the result of a PCA transformation.
5. Unfortunately, due to confidentiality issues, they cannot provide the original features and more background information about the data.
6. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.
7. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
8. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning.
9. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
