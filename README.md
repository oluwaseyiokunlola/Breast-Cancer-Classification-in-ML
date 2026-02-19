# 🧠 Overview

This project focuses on building a machine learning model to classify breast cancer tumors as malignant or benign using diagnostic features. The goal is to assist early detection by applying a supervised learning approach.

A Logistic Regression model was trained and evaluated using the Breast Cancer dataset available in scikit-learn.

# 📊 Dataset

Source: sklearn.datasets.load_breast_cancer()
Samples: 569
Features: 30 numerical diagnostic features

Target:
0 → Malignant
1 → Benign

# 🛠️ Tools & Libraries
* Python
* NumPy
* Pandas
* Scikit-learn

# 🔄 Workflow
* Load the breast cancer dataset from scikit-learn
* Convert data into a Pandas DataFrame
* Separate features and target variable
* Split data into training and testing sets
* Train a Logistic Regression model
* Evaluate model performance using accuracy score
* Build a predictive system for new inputs

# 📈 Model Used
Algorithm: Logistic Regression

## Why Logistic Regression?
* Suitable for binary classification
* Easy to interpret
* Efficient for medical datasets

# ✅ Results
* High accuracy (90% +) achieved on both training and testing datasets
* Model shows strong performance in distinguishing between malignant and benign tumors
