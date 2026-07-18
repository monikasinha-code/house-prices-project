# Housing Price Prediction Project

## Overview
This repository contains the data processing, predictive modeling workflows, and the implementation of a residential housing price estimation tool.

## Project Structure

### 1. Data Merging
*   **Workflow**: Combines numerical and categorical engineered datasets into a unified master file.
*   **Key Files**: `numerical_engineered_data.csv`, `categorical_engineered_data.csv`
*   **Output**: `final_model_ready_data.csv`

### 2. Price Prediction Calculator
*   **Tool**: A custom-built estimation tool featuring a `predict_house_price` function.
*   **Functionality**: Takes user-defined property features (e.g., quality, square footage, year built) as input.

### 3. Random Forest Modeling
*   **Notebook**: Focuses on establishing a baseline using a `RandomForestRegressor`.
*   **Performance**: Achieved an $R^2$ of approximately 0.89.

### 4. Ridge Regression Modeling
*   **Notebook**: Focuses on linear modeling techniques.
*   **Preprocessing**: Implementation of a `Pipeline` including `SimpleImputer` and `StandardScaler`.
*   **Optimization**: Applied `GridSearchCV` for `alpha` tuning.
*   **Performance**: The tuned Ridge model with log-transformed targets achieved an $R^2$ of ~0.91.

## Tableau Presentation
The findings and the predictive logic are being visualized in a Tableau dashboard to communicate regional insights and model performance to stakeholders.# house-prices-project