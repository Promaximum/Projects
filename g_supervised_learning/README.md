# Customer churn

## Project description 
"Beta-Bank" has started losing customers. Every month. Not a lot, but it's noticeable. Bank marketers have calculated that retaining current customers is cheaper than attracting new ones. The task is to forecast whether a customer will leave the bank in the near future. Historical data on customer behavior and contract terminations with the bank have been provided. Build a model with the highest possible F1-score. To pass the project successfully, the F1-score needs to be brought up to 0.59. Check the F1-score on the test dataset independently. Additionally, measure the AUC-ROC, and compare its value with the F1-score.

## Tools & Skills
* Python
* Pandas
* Numpy
* Matplotlib
* Sklearn

## Key Findings

During the project execution, we followed the steps below:

1) We removed three unnecessary columns - RowNumber, CustomerId, and Surname - as they didn't significantly affect the analysis. There were no duplicates in the dataframe, and we replaced null values with zeroes.

2) We examined the class imbalance (1 to 4 ratio) and hypothesized that it affected the model quality, which was confirmed in subsequent steps. We found that all models had lower recall than precision due to the data imbalance, ultimately affecting the F1-score.

3) We confirmed that the class imbalance led to worsened models. The best solution to this problem was to increase class 1 in the training set. We found that balancing the classes led to an increase in the F1-score, an increase in the recall hyperparameter, and a decrease in the precision hyperparameter.

4) We identified the best model, which was Random Forest with balanced classes. This model demonstrated adequate performance, supported by an ROC-AUC score of 0.84. The accuracy of class predictions was quite high at 0.841. Precision was 0.687, Recall was 0.456, Accuracy was 0.841, and F1-score was 0.541.
