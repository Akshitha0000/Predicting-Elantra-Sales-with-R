Elantra Car Sales Prediction Script
Overview:
This R script is designed for analyzing and predicting Elantra car sales based on various factors such as unemployment rates, consumer price index (CPI), Google search queries, and seasonal effects. The script utilizes linear regression modeling techniques to build predictive models and evaluate their performance using historical sales data.

Usage:
Data Loading and Preprocessing: The script loads the dataset containing historical Elantra car sales data. It then splits the data into training and testing sets, with observations from 2012 and earlier used for training and observations from 2013 and 2014 used for testing.

Linear Regression Model Building: The script constructs linear regression models to predict monthly Elantra sales using different combinations of independent variables, including unemployment, CPI, queries, and month. It calculates and reports the multiple R-squared values to assess the goodness of fit for each model.

Modeling Seasonality: The script explores incorporating seasonal effects due to the month by adding the month variable to the regression model. It evaluates the change in model performance and emphasizes the importance of properly modeling month as a factor variable.

Model Evaluation: The script evaluates the performance of the linear regression models on the test set using metrics such as sum of squared errors and R-squared values. It also conducts error analysis to identify periods with the largest absolute prediction errors.
