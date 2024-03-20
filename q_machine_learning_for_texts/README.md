# Wikishop

## Project description 
The online store "Wikishop" is launching a new service. Now users can edit and supplement product descriptions, similar to wiki communities. In other words, customers can suggest their edits and comment on changes made by others. The store needs a tool to identify toxic comments and send them for moderation.

We need to train a model to classify comments as positive or negative. We have a dataset with labels indicating the toxicity of edits.

The goal is to build a model with an F1-score of at least 0.75.

## Tools & Skills
* Python
* Pandas
* Numpy
* Pandarallel
* Tqdm
* Nltk
* Re
* Catboost
* Sklearn
* Imblearn
* Seaborn
* Matplotlib
* Transformers

## Key Findings

During the data loading and preparation for training, we loaded the data, checked for missing values and duplicates, and removed the unnecessary column "Unnamed: 0". We identified the target feature as "lemm_text". We used TfidfVectorizer for text vectorization. Then, we split the data into training and testing sets in a 4:1 ratio.

During model training, we found that the logistic regression model is the best choice for our investigation. This is because the other models, namely Random Forest and CatBoost, showed insufficient F1 scores for our analysis, specifically 0.61 and 0.70, respectively. All models passed the adequacy check compared to the constant model, where the F1 score was 0.18.
