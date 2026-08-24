# Spotify Song Popularity Prediction

Machine learning analysis predicting Spotify song popularity using audio and genre features.

## Overview

This project examines whether Spotify audio and genre characteristics can be used to predict whether a song will be popular.

The analysis uses a dataset containing more than 230,000 Spotify tracks and combines exploratory data analysis with multiple machine learning approaches.

## Exploratory Data Analysis

A separate exploratory data analysis examines patterns in Spotify track popularity, genre, and audio characteristics before predictive modeling.

**[View the Exploratory Data Analysis](https://github.com/jacoby-ramsey/spotify-song-popularity-prediction/blob/facd67fd557bbaf63c86cdc18db34ea9515eec00/eda/Exploratory_Data_Analysis.pdf)**

The EDA explores:

- Distribution and class balance of Spotify popularity scores
- Differences in audio characteristics between popular and non-popular songs
- Popularity patterns and variation across genres
- Relationships between danceability, energy, loudness, and popularity
- Correlations among audio characteristics and popularity
- Standardized audio profiles across genres
- Missing values and duplicate track IDs

## Business Question

Can characteristics of a song be used to identify tracks with a higher likelihood of popularity?

## Tools

- R
- tidyverse
- caret
- randomForest
- ggplot2
- Machine Learning

## Dataset

230,000+ Spotify tracks containing audio characteristics, genre information, and popularity measures.

## Analytical Process

1. Data cleaning
2. Exploratory data analysis
3. Feature engineering
4. Model development
5. Model evaluation
6. Model comparison

## Models

- Logistic Regression
- k-Nearest Neighbors
- Decision Tree
- Random Forest
- Neural Network
- Support Vector Machine
- Stacked Ensemble

## Results

Six classification models were developed and compared using a 46,000+ observation modeling sample.

The strongest standard models achieved approximately 86.5% classification accuracy, while cost-sensitive modeling increased sensitivity to approximately 95.6% when greater emphasis was placed on identifying popular songs.

## Visualizations

Key visualizations include:
- Popularity distributions
- Genre popularity comparisons
- Audio-feature relationships
- Correlation analysis
- Random Forest feature importance
- Model performance comparisons

## Repository Structure

- `scripts/` - R analysis and modeling code
- `images/` - project visualizations
- `report/` - full machine learning project report
- `data/` - dataset information and source documentation
- `explanatory_data_analysis/` - exploratory data analysis and supporting visualizations
