# Credit Default Prediction using Neural Networks

## Overview

This project predicts whether a credit card client will default next month using multiple machine learning models:

- Logistic Regression
- Random Forest
- Multi-Layer Perceptron (Neural Network)

The objective is to compare classical statistical models with a neural network in a real-world financial risk classification problem.

---

## Dataset

Default of Credit Card Clients Dataset (UCI Machine Learning Repository)

- 30,000 clients
- Financial and demographic features
- Binary target: default (1) / no default (0)

---

## Project Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis
3. Feature Scaling
4. Model Training
5. Model Comparison
6. ROC Curve Analysis
7. Precision-Recall Curve Evaluation

---

## Models Compared

- Logistic Regression
- Random Forest
- Neural Network (MLPClassifier)

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Average Precision (PR Curve)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## How to Run

Install dependencies:

pip install -r requirements.txt

Then launch Jupyter Notebook and open:

notebooks/credit_default_analysis.ipynb
