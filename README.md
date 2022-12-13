# Password_strength_analysis

Dataset: https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset 

Here we have a dataset containing 669640 unique passwords, each with an associated strength. 

There are only 2 attributes to worry about here.
* Password - a unique string with various characters.
* Strength - a value from 0-2 representing poor-good-strong.

The pynb file is broken up into a few different sections.
## Data exploration
* Undestanding
* Exploration
## Data preparation
* NLP 
## Data analysis
* Modelling (decision tree and logistic regression)
* Evaluation (scoring and prediction)

It was found that the dataset was very unbalanced but still provided some good results. The data has a 13/74/12 ratio for 0/1/2. Clearly the data is skewed but this is unavoidable and different sampling methods would not help us.
