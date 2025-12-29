# Predicting Salary Using Linear Regression

## Overview
This project builds a linear regression model to predict employee salaries based on years of work experience. The objective is to demonstrate how historical data can support fair and data-driven compensation decisions in a corporate environment.

The final model achieves an R² score of 0.90, indicating strong predictive performance. Model assumptions are validated using residual analysis, and stability is confirmed through cross-validation.

## Problem Statement
During periods of economic slowdown and inflation, organizations must carefully manage hiring costs while maintaining employee motivation. Determining appropriate salary levels for future hires is a common challenge for finance and HR teams.

This project explores whether years of experience can reliably predict salary levels using a linear regression model.

## Dataset
The dataset contains the following variables:
- Years Experience
- Salary

Target variable:
- Salary

## Methodology
- Data loading and inspection
- Exploratory data analysis
- Correlation analysis
- Train-test split
- Linear regression model training
- Model evaluation using R² and RMSE
- Residual analysis to validate assumptions
- 5-fold cross-validation
- Interactive salary prediction

## Results
Model: Linear Regression  
Test R²: 0.90  
Cross-validation R²: 0.89  

The model explains approximately 90 percent of the variation in salary.

## Conclusion
This project demonstrates a complete and well-validated linear regression workflow. The results show that years of experience alone can serve as a reliable predictor of salary, supporting cost-conscious and data-driven hiring decisions.

## Repository Structure
salary-prediction-linear-regression/
- Linear_regression_salary.ipynb
- years_experience_salary_data.csv
- README.md
