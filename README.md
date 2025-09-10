# Fantasy Basketball Prediction Model

This project builds a Gradient Boosting Decision Tree (GBDT) model to predict fantasy basketball points for active NBA players in the upcoming 2025-26 NBA season based on historical game logs (past 3 seasons).

Kaggle Datasets used:
* Player Game Logs (3 seasons): https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores
* Player Database: https://www.kaggle.com/datasets/yagizfiratt/nba-players-database

## Project Description

The goal of this project is to create a dataset for fantasy basketball analysis using NBA game log data from recent seasons. A LightGBM model is trained on this data to predict player fantasy points per game. The project includes data loading, preprocessing, feature engineering (calculating fantasy points), model training, and generating player rankings based on predicted fantasy points.
