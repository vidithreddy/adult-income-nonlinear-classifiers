# Adult Income Dataset - Non-Linear Classifiers (adult-income-nonlinear-classifiers)

## Purpose and Motivation
This project demonstrates a professional machine learning workflow using the UCI Adult Income dataset. It applies three different non-linear classification models—Random Forest, Support Vector Machine (SVM), and XGBoost—to predict whether an individual's income exceeds $50K/year. The goal is to show end-to-end data loading, preprocessing, hyperparameter tuning, and evaluation using modern ML pipelines.

## Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- Data in LIBSVM format provided as `a9a` and `a9a.t`.
- Predicts high-income vs. low-income based on demographic features.

## Features Demonstrated
- Loading LIBSVM data format
- Data preprocessing and conversion
- Grid search with cross-validation
- Hyperparameter tuning
- Test set evaluation
- Comparison of multiple non-linear classifiers

## Folder Structure
adult-income-nonlinear-classifiers/
├── data/
│ ├── a9a
│ └── a9a.t
└── notebooks/
├── AdultIncome_RandomForest.ipynb
├── AdultIncome_SVM.ipynb
└── AdultIncome_XGBoost.ipynb

## Real-World Use Case
Predicting income level based on demographic features is a classic classification problem, useful in marketing, policy planning, and social research. This project demonstrates how to approach such tasks with multiple powerful non-linear classification methods in scikit-learn and XGBoost.