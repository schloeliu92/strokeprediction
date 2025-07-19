# Stroke Risk Prediction using Machine Learning

This repository contains a Python-based machine learning pipeline to predict the likelihood of stroke using clinical and demographic features. The project demonstrates data preprocessing, feature engineering, model training, and performance evaluation — developed as a health data science exercise for applying predictive modeling to real-world stroke data.

---

## Objective

To build and evaluate a classification model that predicts stroke occurrence using structured health records. The model incorporates:
- Demographics (age, gender)
- Clinical indicators (hypertension, heart disease, glucose level, BMI)
- Lifestyle factors (smoking status, work type)

---

##  Dataset

- Source: [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)
- Records: 5,110 patient entries
- Target variable: `stroke` (binary: 0 = no stroke, 1 = stroke)

> Note: Dataset is not included in this repo. Download from the link above and place it in the working directory as `stroke.csv`.

---

## Features & Workflow

-  **Exploratory Data Analysis** (distribution plots, correlations)
-  **Preprocessing**: missing value handling, encoding categorical features
-  **Modeling**:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
-  **Evaluation**:
  - Accuracy, precision, recall, F1 score
  - Confusion matrix and ROC curves

---
