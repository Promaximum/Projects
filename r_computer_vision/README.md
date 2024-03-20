# Project: "Customer age determination" 

## Project description 
In the course of this work, we have the following tasks:

Prepare a report on data exploration.
Train a model to predict age from a photograph.
Condition: The Mean Absolute Error (MAE) should not exceed 8.

## Tools & Skills
* Python
* Pandas
* Numpy
* Tensorflow
* Matplotlib
* Seaborn
* PIL

## Key Findings

We have created a model that predicts age from a photograph. The MAE value on the test set is less than 8. There were a total of 7591 photographs. To improve model training, we split the test set from the training set at a ratio of 1:4.

We used a pre-trained ResNet50 model and trained it without freezing the data. We utilized Adam optimization with a learning rate of 0.001. The batch_size during data loading was set to 16. We used mean_squared_error as the loss function, which helped speed up the training process.

We tested the model for 10 epochs, and by the 10th epoch, the model achieved an MAE value of 6.2028.

In conclusion, we obtained a model that meets the requirements, namely an MAE below 8.
