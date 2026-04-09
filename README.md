# Airline Fare Prediction with Regression and Regularization

This repository contains a cleaned portfolio project based on an airline pricing dataset. The goal is to predict average airfare, compare feature-selection and regularization methods, and estimate how competition affects route pricing.

## Project highlights
- Built multiple regression models to predict airline fares from route and market data
- Compared stepwise selection, exhaustive search, and Lasso regularization
- Identified a 10-predictor model with validation RMSE of **34.89**
- Estimated that Southwest entry on a sample route would reduce predicted fare by about **$43.03**
- Built a second pre-launch model using only variables available before operations begin

## Business questions
1. Which route and market characteristics are most associated with airfare?
2. Which modeling approach performs best on validation data?
3. How much might average fare change if Southwest enters a route?
4. How much accuracy is lost when using only variables available before a route launches?

## Tools used
- Python
- pandas
- matplotlib and seaborn
- scikit-learn
- dmba
- Jupyter Notebook

## Repository contents
```text
.
├── airline_fare_modeling_case_study.ipynb
├── README.md
├── Airfares.csv
└── requirements.txt
```

## Key findings
### Best-performing selected model
The strongest selected linear model used these predictors:
- DISTANCE
- SW_Yes
- VACATION_Yes
- HI
- GATE_Free
- SLOT_Free
- PAX
- E_POP
- S_POP
- E_INCOME
<img width="1753" height="1020" alt="Screenshot 2026-04-09 111321" src="https://github.com/user-attachments/assets/6f9150ea-a9bd-425b-bce9-d29fade65a48" />

### Model comparison
- Selected linear model validation RMSE: **34.89**
- Lasso validation RMSE: **36.00**
- Pre-launch model validation RMSE: **40.23**

### Scenario analysis
For the sample route, the selected model predicted an average fare of **$251.72**.
When Southwest was added to the same route, predicted fare dropped to **$208.69**.

Estimated fare reduction: **$43.03**.
