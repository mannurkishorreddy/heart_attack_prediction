# Heart Attack Prediction Analysis

## Introduction
This repository contains a comprehensive analysis and prediction model focused on heart attack risks. The project utilizes Python libraries like NumPy, Pandas, Seaborn, and Matplotlib for data manipulation and visualization.

## Dataset
The `heart.csv` dataset includes various health metrics like age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate, and others. It consists of 1025 entries with 14 columns, providing a rich dataset for analysis.

## Exploratory Data Analysis
The EDA involves histogram plotting for age distribution, a heatmap for correlation analysis, and a detailed investigation of each feature's impact on heart attack risk.

## Model Building and Evaluation
We employ machine learning models like Linear Regression and XGBRegressor. The models are trained and evaluated using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 Score. A comparative analysis of these models is provided to determine the most effective approach.

## Feature Engineering and PCA
The project explores Principal Component Analysis (PCA) for feature dimensionality reduction, assessing its impact on model performance.

## Cross-Validation
We use K-Fold Cross-Validation for a more robust evaluation of model performance, providing insights into the generalizability of our models.

## Instructions for Use
Run the "Heart Attack Predicton_EDA_Modeling" Notebook using the "heart.csv" data file.
