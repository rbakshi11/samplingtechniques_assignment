# samplingtechniques_assignment
# Credit Card Fraud Detection


## Overview

This assignment focuses on exploring and implementing various sampling techniques to detect credit card fraud using the provided CSV dataset. The goal is to train five different models using different sampling methods and evaluate their accuracy in detecting fraudulent transactions. Models used are CatBoost, XGBoost, LightGBM, Support Vector Classifier (SVC), and Random Forest.

## dataset

The dataset for this assignment is a CSV file containing credit card transactions. The data includes various features such as transaction amount, timestamp and others. Unbalanced categories must be managed, as fraudulent transactions are generally rare compared to legitimate ones.

### File name: credit_card_data.csv

## Sampling techniques

In this assignment we have five different sampling techniques to address the unbalanced nature of the data. Selected techniques are:

1. **Random Sampling:** Selecting instances randomly from a dataset without considering the class distribution.

2. **Stratified sampling:** Ensuring that the proportion of classes in the sample is the same across the dataset.

3. **Under-sampling:** Reducing the number of samples in the majority class to balance the class distribution.

4. **Over-sampling:** Increase the number of samples in the minority class to balance the class distribution.

5. **SMOTE (Artificial Minority Over-sampling Technique):** Creating artificial samples for minority class to remove class imbalance.

## Models

Five different machine learning models will be trained on each of the sampled datasets. The selected models are:

1. **CatBoost**
2. **XGBoost**
3. **LightGBM**
4. **Support Vector Classifier (SVC)**
5. **Random Forest**

## instructions

1. **Loading data:**
   - Load the credit card dataset from "credit_card_data.csv".
   - Understand the structure and characteristics of data sets.

2. **Data preprocessing:**
   - Handle missing values ​​if any.
   - Check and visualize the distribution of classes to understand data imbalance.

3. **Sampling:**
   - Use five sampling techniques to create five different data sets.
   - Ensuring a balance between fraudulent and legitimate transactions in the sample dataset.

4. **Model training:**
   - Train CatBoost, XGBoost, LightGBM, SVC, and Random Forest models on each sampled dataset.

5. **Evaluation of the model:**
   - Evaluate the accuracy of each model on a separate test dataset (not used during training).
   - Comparing the performance of trained models with different sampling techniques.

6. **Results and conclusions:**
   - Compare the effectiveness of each sampling method in improving the accuracy of the model for credit card fraud detection and summarize the results.
