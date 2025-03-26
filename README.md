# Cancer-Classification
# Breast Cancer Classification

## Overview
This project is a machine learning-based classification model for detecting breast cancer using the UCI Breast Cancer dataset. It applies various classification algorithms and evaluates their performance to determine the best model.

## Dataset
The dataset used in this project is fetched from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). It contains features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

## Project Workflow
1. *Importing Required Libraries*
2. *Loading the Dataset*
3. *Data Cleaning and Preprocessing*
4. *Exploratory Data Analysis (EDA) and Visualization*
5. *Handling Class Imbalance using SMOTE*
6. *Train-Test Split*
7. *Model Training and Evaluation*

## Machine Learning Models Used
The following classifiers are implemented and compared:
- Decision Tree Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

## Evaluation Metrics
Each model is evaluated based on the following metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report

## Installation
To run this project, install the necessary dependencies using:
```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib seaborn ucimlrepo
