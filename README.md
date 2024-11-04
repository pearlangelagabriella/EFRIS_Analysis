# German Car Analysis (WIP)

This project analyzes German car data, focusing on trends in car pricing, brand distribution, and fuel consumption. Using machine learning, the project aims to predict car prices based on key features.

## Overview

1. **Data Cleaning**: Removed irrelevant data, handled missing values, and transformed features.
2. **Exploratory Data Analysis**: Visualized car brand distribution, transmission types, and price trends.
3. **Modeling**: Tested multiple regression models to predict car prices.
4. **Evaluation**: Assessed models using R-squared, MSE, and MAE to find the best predictor.

## Key Libraries

- **Pandas**, **NumPy** for data manipulation.
- **Matplotlib**, **Seaborn** for visualization.
- **scikit-learn**, **CatBoost**, **XGBoost** for modeling.

## Machine Learning Models

Various models were tested, with **CatBoost Regressor** achieving the highest R-squared score, making it the preferred model.

## Results

- **High-priced Cars**: Analyzed models priced above 100,000 Euro.
- **Price vs. Fuel Consumption**: Found a weak correlation.
- **Best Model**: CatBoost Regressor performed best.

## Setup

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost xgboost
```
Run the notebook to reproduce the analysis.

## Future Work

- Fine-tune models and add new features.
- Use cross-validation for better evaluation.
