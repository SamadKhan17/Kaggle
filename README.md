Kaggle - Credit Card Fraud Detection

Summary
This project implements a Random Forest Machine Learning model to detect credit card fraud using the SMOTE (Synthetic Minority Over-sampling Technique) method to address class imbalance.

Dataset Overview
The dataset comprises transactions from two days, including 492 fraudulent transactions out of a total of 284,807, resulting in a highly unbalanced dataset where the positive class (frauds) accounts for just 0.172% of all transactions.

Features
The dataset contains only numerical input variables, which are the results of PCA (Principal Component Analysis) transformations. Due to confidentiality, the original features and additional background information cannot be disclosed.
Features V1 to V28 are the principal components obtained from PCA.
Time: Represents the seconds elapsed between each transaction and the first transaction in the dataset.
Amount: The transaction amount, which can be utilized for example-dependent cost-sensitive learning.
Class: The target variable, where 1 indicates a fraud and 0 indicates a legitimate transaction.

Model
Utilized a Random Forest classifier with the SMOTE technique to effectively manage the imbalanced dataset and improve detection accuracy.
