# Soccer-Player-Value-Prediction-using-Machine-Learning
Project Overview
The Player Value Prediction project aims to create a predictive model that estimates the market value of players based on various characteristics and performance metrics. This project can be particularly valuable for clubs and scouts who need to evaluate a player's potential monetary worth relative to their performance and market trends. By predicting a player's value accurately, the model can assist in strategic decisions, such as budgeting for player acquisitions, maximizing returns on player sales, and guiding investments in talent development.

This project leverages multiple machine learning techniques to provide accurate valuation and insight into which attributes most heavily influence a player’s market value. It involves several stages, including data preprocessing, feature engineering, model training, and evaluation.

Dataset information

The dataset was scraped from Sofifa, a platform providing comprehensive player statistics and FIFA game ratings, which are instrumental in analyzing player attributes and values. By accurately predicting a player's value, this model can aid in financial and strategic decisions related to team composition, talent acquisition, and budgeting. The dataset includes player data scraped from Sofifa, containing rich attributes such as:
  1. Demographics: Age, nationality, position, experience, and skill traits.
  2. Performance Statistics: Goals, assists, match ratings, passing accuracy, and defensive contributions.
  3. Market Influence Factors: Positional demand, overall ratings, and contract duration.

Modeling Approach

In this project I have implemented several models to capture the non-linear relationships in player valuation:

  1. Linear Regression – Provides interpretive coefficients.
  2. Random Forest Regressor – Manages complex interactions in features.
  3. XGBoost – High efficiency and accuracy, tuned through parameter optimization.

Evaluation Metrics
MAE and RMSE are used to measure prediction accuracy, with RMSE providing sensitivity to large prediction errors, which is crucial in financial estimations.
