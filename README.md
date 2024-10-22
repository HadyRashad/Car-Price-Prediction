# Loan Default Prediction using Machine Learning

## Competition Overview

This project is part of the **Kaggle Playground Series S4E9** competition, where the goal is to predict whether a borrower will default on a loan. Participants will create machine learning models to classify loan status as either "Default" or "No Default" using a provided dataset.

**[Competition Link: Playground Series S4E9](https://www.kaggle.com/competitions/playground-series-s4e9/overview)**

## Dataset

The dataset includes various features about loan applicants, such as demographic information, financial details, and loan information. The dataset consists of the following key files:

- **train.csv**: Training data used to build the model.
- **test.csv**: Test data for prediction.
- **sample_submission.csv**: Format for the submission file.

## Project Workflow

The project is structured into the following main steps:

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
2. **Feature Engineering**: Creating new features to improve model performance.
3. **Model Building**: Trying different algorithms such as *Logistic Regression*, *Random Forest*, *XGBoost*, and *LightGBM*.
4. **Model Evaluation**: Using cross-validation and F1 score to evaluate model performance.
5. **Submission**: Making predictions on the test set and submitting results.
