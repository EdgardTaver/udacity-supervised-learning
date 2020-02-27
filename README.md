# udacity-supervised-learning
Implementation of the Project 1 of the "Machine Learning - Introduction Nanodegree by Udacity". The main task was use supervised learning algorithms to predict income class of individuals.

## Context

This project is part of the "Machine Learning Introduction" Nanodegree by Udacity, as part of the requriements to graduate. Its objective is to employ several supervised learning techniques to build a model that can predict an individual's income class based on features taken from a 1994 US Census.

## Construction

All the data engineering and modelling was done on the Jupyter notebook available in this repository.

The 1994 US Census was **preprocessed** and **normalized**. Then, the project proceeded exploring different supervised learning algorithms and comparing their results, using techniques such as **grid search**. Finally, we used `features importance` to select only relevant features and, by doing so, increase our model's performance during learning and predicting.

## Results

The best model for our data is **AdaBoost**. After optimizing the hyperparameters, it achieved and **accuracy of 86.63%** and **f-score of 74.25%**.
