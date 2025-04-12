# ESG Performance Prediction Using Financial Indicators

This repository contains the code and data for my MSc dissertation project, which investigates whether financial metrics can predict ESG performance using machine learning and explainable AI. The analysis is conducted on the S&P 500 dataset across sectors.

## Repository Contents

- `Dataset_thesis.xlsx` — Raw dataset including financial and ESG metrics
- `1_Analysis_of_Entire_Dataset.ipynb` — Full dataset ML model development and performance analysis
- `2_Sectoral_Analysis.ipynb` — Sector-wise exploration of ESG predictability

## Objective

To evaluate the relationship between financial indicators and ESG scores using classification models (XGBoost, Random Forest, SVM), feature selection, and SHAP-based interpretability techniques.

## How to Run

1. Open the Jupyter notebooks in order: first `1_Analysis_of_Entire_Dataset.ipynb`, then `2_Sectoral_Analysis.ipynb`.
2. Install required libraries: `pandas`, `scikit-learn`, `xgboost`, `shap`, `matplotlib`, etc.
3. The dataset is already included as `Dataset_thesis.xlsx`.

## Results Summary

- Accuracy of ~88% achieved using XGBoost
- Key features predicting ESG scores include revenue growth, debt-to-equity, and net income
- SHAP helped identify consistent financial drivers of ESG performance

## Author

Arham Rahim | MSc in AI & Adaptive Systems | 2024
