# Naive-Bayes

This notebook is my implementation of the Naive-Bayes classifier that does sentiment analysis on IMDB reviews.

This was a project I developed for a University AI/ML class.

## Dataset

The dataset used, is the "IMDB movie review sentiment classification dataset" and can be found [here](https://keras.io/api/datasets/imdb/)

It consists of 50000 reviews from IMDB, split into 25000 positive and 25000 negative ones. It also includes a test dataset.

## Usage

All you have to do is run the cells in order. This classifier loads the dataset, finds the best hyper-parameters and trains a model based on them. Then it prints its accuracy against the test dataset and lastly compares its score with the same classifier from the *sklearn* library. 
