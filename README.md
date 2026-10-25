# refactored-octo-invention
# Placement Predictor

A beginner machine learning project that predicts whether a student gets placed, based on CGPA and IQ.

## What it does
- Loads a 100-student dataset (cgpa, iq, placement)
- Visualizes the data and splits it 90/10 into train and test sets
- Scales features with StandardScaler
- Trains a Logistic Regression model ( above 80% test accuracy)
- Plots decision regions with mlxtend
- Saves the model with Pickle

## Files
- `Placement_Predictor.ipynb`: the full notebook
- `placement.csv`: the dataset
- `model.pkl`: the trained model

## Note
Small toy dataset, built for learning. Not meant to predict real placements.
