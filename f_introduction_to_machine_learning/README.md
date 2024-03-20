# Tariff recommendation

## Project description 
The mobile operator "Megaline" has found out that many customers are using outdated tariff plans. They want to build a system capable of analyzing customer behavior and suggesting a new tariff: "Smart" or "Ultra". We have data on the behavior of customers who have already switched to these tariffs (from the "Statistical Data Analysis" course project). We need to build a classification model that will select the appropriate tariff. Data preprocessing is not required - we have already done it. The goal is to build a model with the highest possible accuracy, aiming for an accuracy of at least 0.75. You need to independently verify the accuracy on the test dataset.

## Tools & Skills
* Python
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn

## Key Findings

During the course of our work, we have completed the following steps:

1) Explored the dataframe.
2) Split the dataset into training, validation, and test sets with a ratio of 60/20/20.
3) Explored three models: Decision Tree, Random Forest, and Logistic Regression. We selected the most suitable model for investigation and trained it, which turned out to be the Random Forest model with 100 trees and an accuracy of 0.78.
4) Evaluated the quality of the trained model on the test set using the accuracy metric.
5) Checked the model for adequacy using metrics such as accuracy, precision, recall, and F1-score.

We used 1928 responses for model training, which is insufficient. We need to increase the dataset several times to improve accuracy, precision, recall, and F1-score metrics.

Based on the calculations of the aforementioned metrics - accuracy, precision, recall, and F1-score - we can conclude that the model's performance is moderate, with an accuracy of 0.63.
