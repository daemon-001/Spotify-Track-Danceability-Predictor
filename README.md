# Spotify Track Danceability Predictor

This project uses machine learning to predict whether a song from Spotify's top tracks has "High" or "Low" danceability based on its audio features.

## Features

- **Data preprocessing**: Loads and processes Spotify track data
- **Feature engineering**: Creates a binary danceability category based on the median threshold
- **Machine learning model**: Implements a Random Forest classifier
- **Performance evaluation**: Reports classification metrics and feature importance
- **Sample predictions**: Demonstrates predictions on example tracks

## Dataset

The project uses the "*Top_Spotify_Tracks_of_2019.csv*" dataset which contains information about Spotify's top tracks from 2019, including:
- Track name and artists
- Audio features (danceability, energy, loudness, etc.)

## Model

The model classifies songs as having "High" or "Low" danceability based on these audio features:
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo

## Results

The Random Forest classifier achieves good accuracy in predicting danceability categories. Feature importance analysis reveals which audio characteristics most strongly influence a track's danceability.
