Predicting Salary Using Linear Regression

Overview

This project builds a Linear Regression model to predict employee salaries based on years of work experience. The goal is to demonstrate how historical data can be used to support fair, data-driven compensation decisions in a corporate environment.

The final model achieves an R² score of 0.90, indicating strong predictive performance. Model assumptions are validated using residual analysis, and stability is confirmed through cross-validation.

Problem Statement

During periods of economic slowdown and inflation, organizations must carefully manage hiring costs while maintaining employee motivation. Determining appropriate salary levels for future hires is a common challenge for finance and HR teams.

This project explores whether years of experience can reliably predict salary levels and whether a linear regression model can support consistent and transparent salary decisions.

Dataset & Features

The dataset contains the following variables:

Years Experience – Number of years of professional work experience

Salary – Corresponding annual salary

Target Variable:

Salary

Methodology

Data loading and inspection

Missing value checks and descriptive statistics

Exploratory Data Analysis (EDA)

Correlation analysis

Train-test split (80/20)

Linear Regression model training

Model evaluation using R² and RMSE

Residual analysis to validate regression assumptions

5-fold cross-validation to assess generalizability

Interactive salary prediction using a slider widget

Model Assumptions Validation

The following linear regression assumptions were tested and satisfied:

Linearity between experience and salary

Independence of residuals

Homoscedasticity (constant variance of residuals)

Normality of residuals

Residual diagnostics confirmed the suitability of a linear regression model.

Results

Model: Simple Linear Regression

Test Set R²: 0.90

Average Cross-Validation R²: 0.89

The model explains approximately 90% of the variation in salary, with consistent performance across multiple data splits.

Key Insights

Years of experience is a strong predictor of salary

Salary increases follow a clear linear trend

The model generalizes well and shows no signs of overfitting

Suitable for estimating fair salary ranges for future hires

Repository Structure

salary-prediction-linear-regression/
├── Linear_regression_salary.ipynb
├── years_experience_salary_data.csv
└── README.md