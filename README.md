# AInime-suggestions
This project means to give anime suggestions based on your personal ratings for famous anime series.

## MODEL 1 - KNN with cosine similarity


This aproach is avaliable in this [notebook](cosine_similarity.ipynb).

It suggests anime that you will likely high-rate by comparing your ratings with X neighbors, beeing those the one with the most similarity to your ratings, so on suggestings anime they rated well and you did not rate those anime yet.

## MODEL 2 - XGBoost model 

This aproach is avaliable in this [notebook](xgboost.ipynb).

It suggests acording to amount of completed anime by the user, user gender, anime genre, anime episode duration and amount of episodes.

# How to use the models

## all models

Download the dataset on [Kaagle](https://www.kaggle.com/datasets/azathoth42/myanimelist?resource=download&select=anime_cleaned.csv).

Export the .csv files to a folder name "DataSets". (You can create the folder inside this repository in your workspace)

Follow the instructions on the notebook.

* if you change any of the names you can ajust then on the first cells of the notebook, where the directories are set.



