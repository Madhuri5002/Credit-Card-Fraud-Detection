# Credit Card Fraud Detection using ML Techniques

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/4ee15b62-2360-4764-9bb2-581595232873" />

## Overview
This project is a credit card fraud detection system that uses machine learning to classify fraudulent and non-fraudulent transactions. It uses a dataset with transactions that have been pre-processed to protect sensitive user data.
The primary method used for classification is a Logistic Regression model. The project notebook also explores the data through exploratory data analysis (EDA) to understand the dataset's characteristics, such as the distribution of transaction amounts and the relationship between variables.

## Dataset

The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Credit Card Frad Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Methadology

Methodology
This project employs a robust methodology to identify the most effective machine learning model for credit card fraud detection. Several classification algorithms were trained and evaluated on the dataset to compare their performance. The models used include:

- Naive-Bayes

- Logistic Regression

- Random Forest

- Decision Tree

- XGBoost

Each model was trained on the provided credit card transaction data, and their performance was rigorously tested on both the training set and a separate, unseen test set. This dual-evaluation approach is crucial for identifying models that generalize well and avoid overfitting. The accuracy scores of each model on both data sets were compared to determine the best-performing algorithm.

## Conclusion 
Based on the comparative analysis of the various machine learning models, a clear conclusion can be drawn regarding their efficacy in detecting credit card fraud for this project. The evidence from the performance metrics demonstrates that the XGBoost model stands out as the most robust and accurate classifier. It consistently achieved the highest accuracy on both the training and test datasets, which is a critical indicator of its ability to generalize and make reliable predictions on new, unseen data. In contrast, while models like Random Forest and Decision Tree showed high accuracy on the training data, the notable drop in their test data performance suggests they are likely overfitting to the training data. Given these findings, the XGBoost model is conclusively the optimal choice for this fraud detection system.
<img width="1151" height="616" alt="image" src="https://github.com/user-attachments/assets/26b2ca28-71c9-4b83-9990-e61fde2f6bd0" />


