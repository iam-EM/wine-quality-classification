# Wine Quality Classification 🍷
## Project Overview
Small machine learning project classifying red and white wines based on physicochemical features. Compared two models: Decision Tree and Naïve Bayes. Includes feature selection, normalization, and cross-validation.

## Dataset
Source: Wine Quality dataset

Size: 6497 rows, 13 variables (12 features + 1 target type)

## Tools
- Python

- pandas, numpy

- scikit-learn

- matplotlib, seaborn

## Steps
- Data exploration and feature correlation analysis

- Feature selection using Decision Tree importance

- Data normalization (Min-Max scaling)

- Train/test split (90%/10%) with reproducibility

- Model training and evaluation (Decision Tree, Naïve Bayes)

- 10-fold cross-validation for F1-score comparison

## Results
Decision Tree:

- Subset accuracy: 95%

Cross-validated F1-score: 0.970

Naïve Bayes:

- Subset accuracy: 94%

Cross-validated F1-score: 0.960

## Business Application
Automated wine classification to support inventory management and quality control in wineries and distribution centers.
