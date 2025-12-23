# sports-win-predictor
# Sports Game Outcome Predictor

## Overview
This project predicts whether a team will win or lose a game based on pre-game statistics.
The goal is to explore binary classification using logistic regression and to understand how
different performance metrics influence game outcomes.

## Dataset
A synthetic but realistic sports dataset was generated to simulate real-world conditions.
Each row represents a game, with features such as home advantage, scoring trends, and rest days.

**Features:**
- Home vs Away indicator
- Average points scored
- Average points allowed
- Win percentage
- Days of rest

**Target:**
- Win (1) or Loss (0)

## Approach
- Performed exploratory data analysis (EDA) to understand feature relationships
- Trained a logistic regression classifier
- Evaluated performance using accuracy and a confusion matrix

## Results
The model achieved reasonable accuracy on unseen test data, reflecting the inherent
uncertainty of sports outcomes.

## Tools Used
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib

## Future Work
- Experiment with other classification models (KNN, Random Forest)
- Use real-world sports datasets
- Improve feature engineering
