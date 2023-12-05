# Movie Recommendation System

This project implements a Movie Recommendation System using various modeling techniques to predict both the top 10 and worst 10 movies. The dataset comprises movie and rating data sourced from the [MovieLens dataset](https://grouplens.org/datasets/movielens/). The analysis results are concisely presented in the table below:

## Models and Performance Metrics

| Model                           | MAE        | MSE        | RMSE      |
| --------------------------------|------------|------------|-----------|
| Cinematch                       | NA         | NA         | 0.9525    |
| The Netflix Prize               | NA         | NA         | 0.8573    |
| Random Guessing                 | 1.1723     | 2.2712     | 1.5070    |
| Linear Model (Mean Baseline)    | 0.8635     | 1.1395     | 1.0675    |
| Linear Model (Mean + Movie Bias) | 0.7042    | 0.8282     | 0.9100    |
| Linear Model (Mean + Movie and User Bias) | 0.3504 | 0.3127  | 0.5592    |
| Linear Model with Regularized Bias | 0.3532 | 0.3128  | 0.5593    |
| Matrix Factorization            | 1.1296     | 2.0702     | 1.4388    |

## Overview

The project is implemented in R, providing insights into the effectiveness of recommendation models. The analysis is structured to predict both highly rated and poorly rated movies, enhancing user experience.

## Usage

1. **Dataset Exploration**: Explore the provided dataset to gain insights into the movie ratings.
2. **Model Development**: Utilize the implemented models to predict top-rated and low-rated movies.
3. **Performance Evaluation**: Evaluate model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Data Sources

The primary data source for this project is the [MovieLens dataset](https://grouplens.org/datasets/movielens/), offering a rich collection of movie ratings from users. The dataset provides valuable information for training and evaluating recommendation models.

## Acknowledgments

Special thanks to the MovieLens dataset creators and maintainers for providing a valuable resource for research and development in the field of recommendation systems.


