# Stroke-Prediction
<img align="center" alt="Stroke" width="500" src="https://github.com/sanketpatil51/Stroke-Prediction/blob/main/stroke.jpg" >

## Introduction
This dataset project focuses on predicting the likelihood of stroke occurrence based on various health metrics and demographic information. Stroke is a significant cause of disability and mortality worldwide, making early prediction crucial for preventive healthcare. The dataset includes attributes such as age, gender, average glucose level, and body mass index, alongside stroke occurrence as the target variable.

In this analysis, special attention is given to handling class imbalance, as well as detecting and managing outliers in the avg_glucose_level feature. The goal of the project is to build a robust predictive model that can accurately distinguish between individuals at high and low risk of stroke, aiding in early intervention strategies and efficient healthcare management.

## Dataset Description
<img align="center" alt="Stroke" width="500" src="https://github.com/sanketpatil51/Stroke-Prediction/blob/main/stroke.jpg" >

The stroke prediction dataset includes demographic and health-related features to assess the risk factors associated with stroke occurrence. Below is a brief description of each feature:
### id: 
Unique identifier for each individual (not used in modeling).
### gender:
Gender of the individual, represented as "Male," "Female," or "Other."
### age: 
Age of the individual in years, captured as a numerical value.
### hypertension: 
Indicates if the individual has hypertension (0 = No, 1 = Yes).
### heart_disease: 
Indicates if the individual has any form of heart disease (0 = No, 1 = Yes).
### ever_married: 
Marital status, with possible values "Yes" or "No."
### work_type:
Employment type, specifying the individual’s work environment (e.g., "Private," "Self-employed," "Govt_job," "children," "Never_worked").
### Residence_type:
Living environment of the individual, either "Urban" or "Rural."
### avg_glucose_level:
Average glucose level in the blood (mg/dL). May contain outliers requiring preprocessing.
### bmi:
Body mass index of the individual. Missing values may need imputation.
### smoking_status: 
Smoking habits, with possible values "never smoked," "formerly smoked," "smokes," or "Unknown" if data is unavailable.
### stroke:
Target variable indicating whether the individual has experienced a stroke (0 = No, 1 = Yes).
