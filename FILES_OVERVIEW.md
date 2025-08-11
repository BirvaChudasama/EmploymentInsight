# Project Files Overview

This document provides an overview of each file and folder in the repository.

## Folders

### `statisticsdata_canada_labour`
Contains cleaned and raw Labour Force Survey datasets from Statistics Canada.
- **Labour force characteristics by province, seasonally adjusted.csv** – Raw labour force statistics for each province.
- **employment_cleaned.csv** – Processed dataset containing cleaned employment statistics.
- **labour_force_cleaned.csv** – Processed dataset containing cleaned labour force participation data of Labour force characteristics by province, seasonally adjusted.csv.

### `twitter_csvs_data`
Contains CSV files of tweets related to employment trends.
- Raw Twitter data collected via keyword searches.
- Used for sentiment analysis and keyword extraction.

### `twitter_data_specific_keywords`
Contains Twitter datasets filtered by specific employment-related keywords.
- Used to analyze targeted discussions around employment topics.

## Jupyter Notebooks

- **ML modeling 1.ipynb** – First machine learning model implementation for predicting employment trends.
- **ML modeling 2.ipynb** – Second machine learning model with additional tuning and performance evaluation.
- **cleaning_all_csvs.ipynb** – Data cleaning scripts for all CSV datasets.
- **dimension_reduction & feat_selection.ipynb** – Feature selection and dimensionality reduction experiments.
- **sentiment_analysis.ipynb** – Performs sentiment analysis on Twitter datasets.
- **spec_keyword_tweet_cleaning.ipynb** – Cleans tweets from the specific keywords dataset `twitter_data_specific_keywords`.
- **visualization.ipynb** – Generates visualizations for employment and unemployment trends.

## Other Files

- **README.md** – Project description, features, and instructions.
- **requirements.txt** – List of Python libraries required to run the project.
