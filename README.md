# Netflix-Movie-recommendation
collaborative filtering based approach to recommend movies to users

## Data:
https://www.kaggle.com/netflix-inc/netflix-prize-data/data

The data contains users ids and movie ids along with their ratings from 1 to 5

## Problem Statement:
Given a user and a movie predict the ratings which he/she would give for the movie

## Metric:
1. RMSE
2. MAPE

## Results on test data:

1. Suprise Baseline model: RMSE=1.07303,MAPE=35.0499
2. Suprise KNN baseline(user similarity): RMSE=1.07264,MAPE=35.0209
3. Suprise KNN baseline(movie similarity):RMSE=1.072758,MAPE=35.02269
4. SVD : RMSE:1.0726,MAPE=35.0195
