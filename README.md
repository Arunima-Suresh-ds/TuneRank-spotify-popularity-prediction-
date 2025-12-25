# Spotify Popularity Prediction (TuneRank)

## Overview
Genre-aware music popularity prediction using audio features, classical
machine learning models, and generative AI for insight generation.

## Objective
To predict song popularity levels (Low, Medium, High) based on Spotify audio
features and convert model predictions into actionable promotion insights.

## Dataset
Spotify audio features dataset (~40,000 tracks) containing:
- Danceability
- Energy
- Valence
- Tempo
- Loudness
- Acousticness
- Speechiness
- Instrumentalness
- Liveness
- Duration

## Approach
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Post-modeling insight generation using GenAI

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting (final model)

## GenAI Component
A Large Language Model (LLM) was used in the post-prediction stage to generate
human-readable music promotion recommendations based on predicted popularity
class and model confidence.  
No generative model was trained; GenAI is used strictly for insight generation.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Generative AI (LLM-based recommendation generation)
