# Movie Recommendation Project 2024

## Project Overview

The **Movie Recommendation Project 2024** is a data science project that involves building a movie recommendation system using the Surprise library. The project is part of the Movie Recommendation Competition 2024. The goal is to develop a model that predicts user ratings for movies based on historical data.

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

-Data Overview
This dataset consists of several million 5-star ratings obtained from users of the online MovieLens movie recommendation service. The MovieLens dataset has long been used by industry and academic researchers to improve the performance of explicitly-based recommender systems, and now you get to as well!

For this Predict, we'll be using a special version of the MovieLens dataset which has enriched with additional data, and resampled for fair evaluation purposes.

-Source
The data for the MovieLens dataset is maintained by the GroupLens research group in the Department of Computer Science and Engineering at the University of Minnesota. Additional movie content data was legally scraped from IMDB

-Supplied Files
-**genome_scores.csv - a score mapping the strength between movies and tag-related properties. Read more here
genome_tags.csv - user assigned tags for genome-related scores
imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
sample_submission.csv - Sample of the submission format for the hackathon.
tags.csv - User assigned for the movies within the dataset.
test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.

## Results
The model's performance is evaluated using RMSE (Root Mean Squared Error) through cross-validation. The optimal hyperparameters are determined using GridSearchCV.
This will generate a submission.csv file containing the predicted ratings for the test dataset.
