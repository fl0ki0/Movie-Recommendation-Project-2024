# Movie Recommendation Project 2024

## Project Overview

The **Movie Recommendation Project 2024** is a data science project that involves building a movie recommendation system using the Surprise library. The project is part of the ALX Movie Recommendation Competition 2024. The goal is to develop a model that predicts user ratings for movies based on historical data.

## Table of Contents

- [Project Description](#project-description)
- [Data Description](#data-description)
- [Results](#results)
  

## Project Description

This project involves:
- Loading and processing movie-related data.
- Building and evaluating a recommendation model using the Surprise library.
- Optimizing the model using hyperparameter tuning with GridSearchCV.
- Generating predictions and preparing a submission file.

## Data Description

The dataset includes the following CSV files:
- `train.csv`: Training data containing user ratings.
- `test.csv`: Test data for generating predictions.
- `movies.csv`: Movie metadata.
- `tags.csv`: Tags associated with movies.
- `genome_scores.csv`: Scores for movie genomes.
- `genome_tags.csv`: Tags for movie genomes.

##Results
The model's performance is evaluated using RMSE (Root Mean Squared Error) through cross-validation. The optimal hyperparameters are determined using GridSearchCV.
This will generate a submission.csv file containing the predicted ratings for the test dataset.
