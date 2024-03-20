# Project: "Taxi order forecasting"

## Project description 
Company "Cool taxi" has collected historical data on taxi orders at airports. To attract more drivers during peak demand periods, it is necessary to forecast the number of taxi orders for the next hour. A model for such prediction is required.

The RMSE metric value on the test set should not exceed 48.

## Tools & Skills
* Python
* Pandas
* Pathlib
* Matplotlib
* Statsmodels
* Sklearn
* Lightgbm
* Catboost

## Key Findings

The entire month of July was analyzed, followed by a 2-day period. A trend was identified indicating that orders increase over time, peaking at midnight. The data was checked for stationary time series. Features were created for the month, day of the week, lagged features, and moving averages. Missing values were then removed, resulting in a table with 29 features ready for model building.

The dataset was split into test, training, and validation sets. Models were trained using linear regression, decision tree, and random forest algorithms. The best RMSE value was obtained with LGBM.

In the end, the RMSE was 41.34, which is less than 48, meeting the task requirements.
