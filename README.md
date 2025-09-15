# AIPI 590 - XAI - Interpretable ML 

### 🛒 Telco Customer Churn Analysis

This repository contains my submission for the Explainable AI (Interpretable ML) assignment. The project explores customer churn in the Telco Customer Churn dataset using Linear Regression, Logistic Regression, and a Generalized Additive Model (GAM). The goal is to evaluate model assumptions, interpretability, and predictive performance, and to provide recommendations for the telecommunications company.

### 📊 Dataset

The dataset used is [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), originally from Kaggle. It contains information about customer demographics, account information, and service usage, with churn (Yes/No) as the target variable.

### 💻 How to Run the Notebook in Google Colab

- Open the notebook directly in Google Colab by clicking this badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ailina-aniwan/xai-interpretable-ml/blob/main/telco_churn_analysis.ipynb)

- Run all cells in order (click on `Run all`). The notebook is self-contained: it loads the dataset directly from an online source and reproduces all analysis.

### ⚙️ Requirements

Python libraries used in this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- pygam

(See `requirements.txt` for details)

### 📌 Assignment Tasks Covered

- Exploratory Data Analysis (EDA): Assumption checks with summary statistics, correlations, and plots.
- Linear Regression: Model fit, coefficient interpretation, residual diagnostics.
- Logistic Regression: Model fit, odds ratio interpretation, performance evaluation.
- Generalized Additive Model (GAM): Non-linear effects captured and visualized with smooth terms.
- Model Comparison: Discussion of strengths/weaknesses and recommendation for best model.

### ✨ Recommendation

Based on performance and interpretability, the GAM is recommended as the primary model for identifying at-risk customers, while Logistic Regression remains a useful baseline for clear communication with stakeholders.