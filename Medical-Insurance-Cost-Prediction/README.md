# Medical Insurance Cost Analysis and Prediction

## Project Overview

This project explores factors associated with medical insurance charges using Python. It examines relationships between individual characteristics and insurance costs through data exploration, visualization, and regression modeling.

The analysis also evaluates different regression approaches to understand how well they explain and predict medical insurance charges.


## Python Libraries

- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Regression modeling and model evaluation



## Key Findings

- Smoking status was an important predictor of medical insurance charges in the dataset.
- Using all six predictors improved the training R² from 0.6222 to 0.7504 compared with using smoking status alone.
- The polynomial regression pipeline achieved a training R² of 0.8452.
- On the test data, Ridge regression achieved an R² of 0.6761. Applying a second-order polynomial transformation increased the test R² to 0.7836.

Overall, the results show that using additional features improved the fit to the training data, while the second-order polynomial transformation improved Ridge regression performance on the test data.


## View Full Analysis

[View the Medical Insurance Cost Analysis Notebook](YOUR_NOTEBOOK_FILENAME.ipynb)
