# Titanic Survival Prediction

## Overview
This project analyzes the [Titanic Huge Dataset](https://www.kaggle.com/datasets/marcpaulo/titanic-huge-dataset-1m-passengers) and builds a predictive model to determine passenger survival. The dataset contains one million entries and is used to explore various machine learning techniques for classification.

## Features
- **Data Wrangling & Preprocessing**: Handling missing values, encoding categorical variables, and feature selection.
- **Exploratory Data Analysis (EDA)**: Visualizing survival rates, passenger demographics, and correlations.
- **Model Training & Evaluation**: Using Decision Trees and hyperparameter tuning with RandomizedSearchCV.
- **Experiment Tracking**: Integrated with MLflow for tracking model performance.

## Results
- The model achieves an accuracy of **86.53%** F1-Score on the testing dataset.
- Key insights from EDA:
  - **Women had a higher survival rate than men.**
  - **First-class passengers had a better chance of survival.**

## Future Improvements
- Implement additional models such as Random Forest and XGBoost.
- Optimize feature engineering for better model performance.

## License
This project is licensed under the MIT License.
