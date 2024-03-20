# Project 'Car Valuation'

## Project description 
A used car sales service 'Not damaged, not repainted' is developing an application to attract new clients. In it, users can quickly determine the market value of their car. Historical data is available: technical specifications, configurations, and prices of cars. It is necessary to build a model to determine the value.

## Tools & Skills
Python, Pandas, Numpy, Matplotlib, Seaborn, Lightgbm, Catboost, Category_encoders, Sklearn

## Key Findings

An analysis of models was conducted, during which we evaluated the quality of the models relative to a constant model. The RMSE for the constant model was 4938.143. The lowest RMSE was achieved when using the CatBoostRegressor model, also at 4938.143.

Therefore, the CatBoostRegressor model was recommended.
