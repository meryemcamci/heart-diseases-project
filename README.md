# 🫀 Predicting Heart Disease Project

This project focuses on predicting the presence of heart disease in patients using various health-related attributes. The analysis includes exploratory data analysis (EDA), visualization, and a machine learning model to classify patients based on whether they are likely to have heart disease.

## 📌 Goal of this Project

To explore patient data and build a classification model that can predict whether a patient is likely to have heart disease (HeartDisease = 1) based on features like age, chest pain type, cholesterol, and other clinical variables.

## Dataset

* Source: Heart Disease UCI Dataset
* Rows: 918
* Columns: 12 (both categorical and numerical)

**Key Features**: 

* Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS
* RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease

## Exploratory Data Analysis (EDA)

* Count plots were used to analyze the distribution of categorical features.
* A **correlation heatmap** was generated to assess relationships between variables and identify potential predictors of heart disease.
* Feature encoding was performed where necessary (e.g., converting categorical variables into **dummy variables**).

## Machine Learning Model

* A classification model kNN was trained and evaluated.
* Model performance was measured using metrics like accuracy.
* Feature importance was examined to understand which variables most influenced the prediction.

## 📌 Key Insights

* Males and patients with atypical or asymptomatic chest pain showed higher rates of heart disease.
* ST_Slope, ExerciseAngina, and ChestPainType were among the strongest predictors of heart disease.
* A notable class imbalance because of the male-female balance was handled appropriately before model training.

## Files

**Predicting Heart Disease Project.ipynb**: The full notebook with analysis, visualizations, and modeling steps.
README.md: This file.

## Future Improvements

* Try other classification models (e.g., SVM, XGBoost).
* Implement hyperparameter tuning.
* Improve feature engineering and handle outliers more robustly.

