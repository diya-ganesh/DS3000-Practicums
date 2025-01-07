# Predictive Modeling for Diabetes Risk

**This project, developed as part of DS3000, explores predictive modeling techniques to identify individuals at risk of developing diabetes. The analysis uses a dataset provided by the CDC's Behavioral Risk Factor Surveillance System (BRFSS), incorporating a variety of health and demographic indicators.**

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Project Objectives](#project-objectives)
- [Features](#features)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction

Diabetes affects millions of individuals in the United States, and many remain unaware of their condition or risk level. This project leverages machine learning techniques to develop a predictive model for identifying individuals at risk. The dataset includes over 250,000 records with 22 health and demographic variables, such as BMI, smoking status, physical activity levels, and healthcare access.

The project aims to:
1. Explore patterns between health indicators and diabetes status.
2. Develop, optimize, and evaluate machine learning models for diabetes prediction.

## Data

The dataset (`diabetes_health_indicators.csv`) includes:
- **Diabetes Status**: Target variable (0 = No diabetes, 1 = Pre-diabetes, 2 = Diabetes).
- **Health Indicators**: BMI, smoking habits, alcohol consumption, physical activity, and more.
- **Demographic Features**: Age, gender, education level, and income bracket.

## Project Objectives

1. **Data Preparation**:
   - Evaluate variable types and preprocess for machine learning.
   - Handle missing, invalid values, and outliers.
2. **Feature Engineering**:
   - Identify and encode categorical, discrete, and continuous variables.
   - Scale numerical features for better model performance.
3. **Model Development**:
   - Split the data into training and testing subsets.
   - Train, tune, and evaluate predictive models (e.g., logistic regression).
4. **Analysis and Insights**:
   - Provide visualizations and insights on the factors contributing to diabetes risk.

## Features

- **Data Preprocessing**: 
  - Identifies and prepares data types for machine learning.
  - Handles missing and invalid data systematically.
- **Exploratory Data Analysis**:
  - Generates descriptive statistics and visualizations.
  - Identifies relationships between variables and diabetes risk.
- **Model Development**:
  - Trains and tunes machine learning models using scikit-learn.
- **Performance Evaluation**:
  - Measures accuracy, precision, recall, and other metrics for model evaluation.

## Usage

1. **Set Up Environment**:
   - Install required libraries:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn
     ```

2. **Run the Notebook**:
   - Open and execute `Diabetes_Risk_Assessor.ipynb` using Jupyter Notebook or Google Colab.

3. **Analyze Results**:
   - Explore visualizations and model performance metrics to understand key predictors of diabetes risk.

## Contributors

- **Diya Ganesh**, **Colin Carnish**, **Jasmine McCoy**: Developers and analysts.

---
