# White Wine Quality Prediction Using Machine Learning

## Project Overview

This project applies machine learning classification algorithms to predict white wine quality using physicochemical properties. Three classification models were developed and compared to evaluate their predictive performance.

## Project Objectives

- Explore and clean the white wine quality dataset.
- Analyse the distribution of wine quality scores.
- Prepare data for machine learning classification.
- Develop and compare three classification algorithms.
- Evaluate model performance using accuracy, precision, recall, and F1-score.
- Identify the best-performing model.

## Dataset

The dataset contains 4,898 wine samples with 11 physicochemical input features, including acidity, residual sugar, chlorides, density, pH, sulphates, and alcohol content.

Wine quality scores were converted into binary classes:

- **0:** Quality score of 6 or below
- **1:** Quality score above 6

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

## Machine Learning Models

1. Random Forest Classifier
2. Logistic Regression
3. Support Vector Classifier (SVC)

## Model Performance

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Random Forest | 91.15% | 89.71% | 92.98% | 91.32% |
| Logistic Regression | 73.05% | 73.08% | 73.08% | 73.08% |
| Support Vector Machine | 69.27% | 67.62% | 74.12% | 70.72% |

These are preliminary results from the original notebook. The evaluation should be repeated after correcting potential data leakage caused by applying SMOTE before the train-test split.

## Key Findings

Random Forest achieved the highest reported classification performance among the three algorithms. Logistic Regression and Support Vector Machine produced lower scores.

Further evaluation on an untouched test set is required before drawing reliable conclusions about generalisation performance.

## Future Improvements

- Apply SMOTE only to the training dataset.
- Use feature scaling where appropriate.
- Perform cross-validation and hyperparameter tuning.
- Examine confusion matrices and class-specific performance.
- Compare results on an untouched test set.


Data Analyst | Python | SQL | Power BI | Machine Learning
