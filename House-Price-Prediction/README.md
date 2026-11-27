# House Price Analysis and Prediction | King County, Washington

## Project Overview

This project explores residential property sales in King County, Washington, using Python to analyze housing data and predict house prices. It examines how property characteristics, including living area, bedrooms, bathrooms, construction grade, and waterfront status, relate to selling prices.

The analysis combines data exploration, visualization, and regression modeling to identify patterns in housing prices and evaluate how well different models explain and predict property values.


## Tools 

- **Python** – Data analysis and predictive modeling
- **Pandas** – Data manipulation and exploration
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Regression modeling and model evaluation
- **Jupyter Notebook** – Code execution and documentation


## Key Findings

- Larger living areas and higher construction grades were associated with higher house prices.
- Multiple linear regression achieved a training R² of 0.6577, compared with 0.4928 when using living area alone.
- The regression pipeline achieved a training R² of 0.7513.
- On the test data, Ridge regression achieved an R² of 0.6479, which increased to 0.7003 after applying a second-order polynomial transformation.

These results show that combining housing features improved the fit to the training data, while the second-order polynomial transformation improved Ridge regression performance on the test data.


## View Full Analysis

[View the House Price Analysis Jupyter Notebook](House_Sales_King_County_Analysis.ipynb)

