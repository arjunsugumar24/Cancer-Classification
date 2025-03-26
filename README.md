# Cancer-Classification

## Breast Cancer Recurrence Prediction

This repository contains a complete end-to-end machine learning project focused on predicting breast cancer recurrence. Using the Breast Cancer dataset from the UCI Machine Learning Repository, the project demonstrates data cleaning, preprocessing, handling class imbalance with SMOTE, and evaluating various classification algorithms.

## Overview

- **Dataset:** The Breast Cancer dataset, originally created in 1988, comprises 286 instances described by 9 features. The dataset includes clinical and gynecological attributes such as age, tumor size, menopausal status, and more.
- **Objective:** Predict the possibility of breast cancer recurrence in women using several machine learning algorithms.
- **Techniques:** Data cleaning, feature engineering, SMOTE for oversampling, and model evaluation using accuracy metrics, confusion matrix, and classification reports.

## Data Acquisition

The dataset is obtained using the `ucimlrepo` package:

```python
from ucimlrepo import fetch_ucirepo

# Fetch dataset (ID: 14 corresponds to Breast Cancer)
breast_cancer = fetch_ucirepo(id=14)
X = breast_cancer.data.features
y = breast_cancer.data.targets
