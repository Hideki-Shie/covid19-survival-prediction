# COVID-19 Survival Prediction — Logistic Regression

A machine learning project that predicts COVID-19 patient survival outcomes using logistic regression. Built in Python as part of STAT 319 (Elementary Mathematical Statistics) at Penn State.

---

## Overview

This project applies binary classification to a large medical dataset to predict whether a patient will survive or die from a COVID-19 infection. Two logistic regression models were trained, evaluated, and compared using standard classification metrics.

---

## Results

Both models achieved consistent performance with default parameters (`C=1.0`, `penalty=l2`, `solver=liblinear`):

| Metric | Score |
|--------|-------|
| Accuracy | 98% |
| Weighted Precision | 0.97 |
| Weighted Recall | 0.98 |
| Weighted F1-Score | 0.97 |

The identical performance across both models confirmed that the default hyperparameters were optimal for this dataset.

---

## Project Structure

The notebook is organized into four stages:

1. **Data Cleaning** — handled missing values, removed inconsistencies, and prepared the dataset for analysis. Proper cleaning was prioritized given the size and complexity of the medical dataset.
2. **Data Visualization** — explored distributions and patterns in patient data to surface insights before modeling.
3. **Training and Prediction** — trained two logistic regression classifiers to predict survival outcomes.
4. **Model Comparison** — evaluated both models using accuracy, precision, recall, F1-score, and confusion matrix.

---

## Technologies Used

- **Language**: Python
- **Libraries**: scikit-learn, pandas, matplotlib
- **Environment**: Jupyter Notebook

---

## Key Concepts Demonstrated

- Binary classification with logistic regression
- Data cleaning and preprocessing on large real-world datasets
- Exploratory data analysis and visualization
- Model evaluation: accuracy, precision, recall, F1-score, confusion matrix
- Hyperparameter analysis and model comparison

---

## Notes

- This was a group project completed with Nabeel Ahmed and Saiid Koroma.
- The notebook (`project.html`) contains the full code, visualizations, and written analysis.
