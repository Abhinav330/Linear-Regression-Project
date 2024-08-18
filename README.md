[![Codacy Badge](https://app.codacy.com/project/badge/Grade/53d63a02e5ba41df9f48cf08ceb6d135)](https://app.codacy.com/gh/Abhinav330/Linear-Regression-Project-on-House-Pricing/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Linear-Regression-Project-on-House-Pricing/seaborn)



# Linear-Regression-Project-on-House-Pricing

# Code Summary

This Python notebook is a simple housing price prediction model using linear regression. It imports necessary libraries, loads the 'USA_Housing.csv' dataset, preprocesses the data, visualizes it, builds a linear regression model, and allows for predicting house prices based on user input.

## Data Loading and Preprocessing

The script starts by importing essential libraries, loading the 'USA_Housing.csv' dataset using pandas, and performing data preprocessing:

- Drops the 'Address' column, which is not required for analysis.- Rounds the numeric columns to integers.
- Renames some columns for readability.

## Data Visualization

Data visualization is performed with various plots:
- A heatmap is used to check for missing values.
- Histograms and bar plots show the distribution of house prices and relationships between variables like 'House Age' and 'Price'.
- A heatmap of the correlation matrix visualizes feature correlations.
- A joint plot shows a hexbin plot and a kernel density estimate plot of 'Area Population' vs. 'Price'.

## Model Building

The code then proceeds to build a linear regression model:
- Splits the data into feature variables ('x') and the target variable ('y') using `train_test_split`.
- Imports `LinearRegression` from scikit-learn and initializes the model.
- Fits the model to the training data.
- Makes predictions on the testing data.

## Model Evaluation

The script evaluates the linear regression model's accuracy using the R-squared (R2) score:
- Imports `r2_score` from scikit-learn and calculates the R2 score.
- Prints the model's accuracy as a percentage.
- Plots the actual vs. predicted house prices for visual comparison.

## User Interaction

The script allows users to input values for 'Area Income,' 'House Age,' 'No. of rooms,' and 'Area Population' to predict the house price:
- Prompts users for input and creates a DataFrame with the input values.
- Uses the trained model to predict the house price based on user input.
- Displays the predicted price in both thousands of dollars and crores of rupees.
- Asks if the user wants to continue predicting house prices.

## References
- Chen, N. (2022). House Price Prediction Model of Zhaoqing City Based on Correlation Analysis and Multiple Linear Regression Analysis. Wireless Communications and Mobile Computing, 2022, pp.1–18. doi:<https://doi.org/10.1155/2022/9590704>.
- SASIKANTH (2018). USA Housing. [online] Kaggle.com. Available at: https://www.kaggle.com/datasets/kanths028/usa-housing [Accessed 18 Aug. 2024].
- scikit-learn developers (2019). sklearn.linear_model.LinearRegression — scikit-learn 0.22 documentation. [online] Scikit-learn.org. Available at: <https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html>.
‌

