# Basic Machine Learning Projects

This repository contains projects showcasing fundamental machine learning techniques, including regression and classification. Each project addresses a real-world problem and demonstrates the complete machine learning workflow, from data preprocessing to evaluation and insights.

---

## Table of Contents
1. [Project 1: BMI Prediction Using Regression](#project-1-bmi-prediction-using-regression)
2. [Project 2: Weather Type Classification](#project-2-weather-type-classification)

---

### Project 1: BMI Prediction Using Regression

#### Overview
This project focuses on predicting **Body Mass Index (BMI)** using data on eating habits and physical activity. The dataset includes records from individuals aged 14 to 61 across Mexico, Peru, and Colombia. The objective is to identify the most significant factors influencing BMI and analyze the relative impact of eating habits and physical condition variables.

#### Key Details
- **Dataset**: 17 attributes, 2,111 records, collected via an online survey.
- **Target Variable**: BMI (calculated using height and weight).
- **Features**: Grouped into two categories:
  - **Eating Habits**: High-calorie food consumption, vegetable consumption, daily water intake, etc.
  - **Physical Condition**: Physical activity levels, calorie monitoring, technology usage, etc.

#### Methodology
1. **Regression Models Used**:
   - Linear Regression
   - Lasso Regression
   - Support Vector Regression (SVR)
   - Random Forest Regression
2. **Steps**:
   - Baseline modeling with all features.
   - Grouped analysis comparing eating habits and physical condition.

#### Insights
The analysis highlights key factors affecting BMI and offers data-driven recommendations for managing BMI effectively.

---

### Project 2: Weather Type Classification

#### Overview
This project aims to classify **Weather Type** using meteorological, atmospheric, and environmental factors. Accurate classification supports critical sectors like agriculture, transportation, and disaster management by improving forecasting capabilities.

#### Key Details
- **Dataset**: 14 features grouped into meteorological attributes, atmospheric conditions, environmental factors, and derived metrics.
- **Target Variable**: Weather Type (categorical: sunny, rainy, cloudy, snowy).
- **Features**:
  - **Meteorological Attributes**: Temperature, humidity, wind speed, precipitation, cloud cover.
  - **Atmospheric Conditions**: Atmospheric pressure, UV index.
  - **Environmental Factors**: Season, visibility, location.
  - **Derived Metrics**: Heat index, precipitation intensity.

#### Methodology
1. **Classification Models Used**:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Gradient Boosting Classifier
2. **Steps**:
   - Data preprocessing (normalization and encoding).
   - Model training, evaluation, and hyperparameter tuning.
   - Evaluation metrics: Accuracy, precision, recall, F1-score, and confusion matrix.

#### Business Impact
Accurate weather classification enhances decision-making and resource management in weather-dependent sectors.

---

## Repository Structure

```plaintext
/Basic Machine Learning Projects
│
├── Project_1_BMI_Prediction/
│   ├── data/             # Dataset for BMI prediction
│   ├── code/             # Python scripts for data preprocessing, modeling, and evaluation
│   └── README.md         # Details about the BMI prediction project
│
├── Project_2_Weather_Classification/
│   ├── data/             # Dataset for weather classification
│   ├── code/             # Python scripts for data preprocessing, modeling, and evaluation
│   └── README.md         # Details about the weather classification project
│
└── README.md             # This file (repository-level README)
