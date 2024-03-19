# Prediction of housing prices

## Project description 
In this project, we need to train a linear regression model on housing data in California in 1990. Based on the data, we need to predict the median house value in a residential area. Let's train the model and make predictions on the test set. We will evaluate the model's performance using the RMSE, MAE, and R2 metrics.

## Tools & Skills
Python, Pandas, Numpy, Pyspark, Seaborn

## Key Findings

Within the project, the following steps were taken:

Initialized a local Spark session.
Explored the data for missing values. Missing values were removed due to their small quantity.
Transformed the column with categorical values using the One Hot Encoding technique.
Built two linear regression models on different datasets.
Compared the results of linear regression models on two datasets using the RMSE, MAE, and R2 metrics.
By building two linear regression models on different datasets (using all data and only numerical data, excluding categorical ones), it was found that all three metrics, namely RMSE, MAE, and R2, indicate that the first model, which contains all features, performs better.
