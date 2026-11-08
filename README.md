# 📉 Customer Churn Prediction

**Customer analytics · Classification · Model interpretation**

## Overview
An end-to-end machine learning case study for identifying telecom customers at risk of churn. The business motivation is to support targeted retention efforts by estimating churn risk and examining relevant customer characteristics.

**[View the Jupyter notebook](telecom_ml_pipline.ipynb)**

## Problem
Predict customer churn from contract, customer, service, and billing information. Compare alternative classification methods while paying attention to evaluation and model interpretability.

## Workflow
1. Join customer and service-related tables.
2. Clean missing values, standardize types, and construct the target.
3. Prepare and encode features.
4. Train and compare classification models, including logistic regression, random forest, and CatBoost.
5. Evaluate with ROC AUC and other classification metrics.
6. Investigate influential features to inform possible retention strategies.

## Tools
`Python` · `pandas` · `scikit-learn` · `CatBoost` · `SHAP` · `Matplotlib` · `Seaborn`

## Reported results
The original project README reports CatBoost as the leading model with **cross-validation ROC AUC = 0.8880** and **test ROC AUC = 0.9246**. These are results reported in the original project documentation and should be checked against the notebook before being used in a résumé.

Potential churn-related factors discussed in the project include customer tenure, contract type, monthly charges, and payment method.

## Run
```bash
pip install jupyter pandas numpy scikit-learn catboost matplotlib seaborn shap
```

Open `telecom_ml_pipline.ipynb` in Jupyter. The original input datasets may not be bundled with the repository.

## Project provenance
Notebook copied from [the original project](https://github.com/HendlessWizzard/Preventing_Customer_Churn). README edited for a concise English-language portfolio.