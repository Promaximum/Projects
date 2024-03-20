# Project: "Telecom" 

## Project description 
The telecommunications operator "TeleDom" wants to combat customer churn. To do this, its employees will start offering promo codes and special conditions to anyone planning to terminate their services. To proactively identify such users, "TeleDom" needs a model that will predict whether a subscriber will terminate their contract. The operator's team has collected personal data about some customers, as well as information about their tariffs and services. The task is to train a model on this data to predict customer churn.

## Tools & Skills
* Python
* SQL
* Pandas
* Numpy
* Psycopg2
* Matplotlib
* Seaborn
* Torch
* Sqlalchemy
* Sklearn
* Catboost
* Tensorflow
* Tqdm

## Key Findings

The following results were obtained for the best cross-validation metric parameters, excluding the constant model and the neural network model:

* Constant Model: 0.5
* Logistic Regression: 0.8447910385752312
* Decision Tree: 0.8557099026427637
* Random Forest: 0.8820026067326501
* Catboost: 0.8913367501507419
* Neural Network Model: Accuracy: 0.7791027825099376

During testing, the Catboost model achieved a ROC AUC metric value of 0.92, which exceeds the specified task requirement (0.85). By applying the class balancing method of Upsampling, we were able to improve the model's quality metric. We also tested the model on a dummy trap.

To improve the model's performance, we can suggest conducting more regular surveys (panel), collecting a larger array of survey data, and clearly recording the contract expiration date and total customer expenses to conduct research more effectively in the next iteration. The model can also be used to improve customer flow, taking into account the company's weaknesses.
