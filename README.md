# Kernelized-SVM-with-Custom-Boosting-Bias-Variance-Analysis-on-Imbalanced-Financial-Risk-Data
Project Overview

This project presents a comparative study of margin-based and ensemble-based machine learning models for credit default risk prediction using the UCI Credit Card Default dataset.

The objective was to:

Implement a dual-form Support Vector Machine (SVM) from scratch using quadratic programming.

Compare its performance against ensemble methods including AdaBoost, Random Forest, and Gradient Boosting.

Handle class imbalance using SMOTE.

Evaluate models using ROC-AUC instead of accuracy due to skewed class distribution.

Interpret model behavior using SHAP explainability techniques.

Key Results

Gradient Boosting achieved the highest ROC-AUC (~0.77).

Ensemble methods significantly outperformed kernel SVM on structured tabular financial data.

SHAP analysis revealed repayment status features as dominant predictors of default risk.

Technical Highlights

Custom dual SVM implementation using cvxopt

RBF kernel and margin maximization

Boosting vs bagging comparison

Bias-variance tradeoff analysis

Cross-validation for robustness

Model interpretability with SHAP
