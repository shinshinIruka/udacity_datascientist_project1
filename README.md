# README: Seattle Airbnb Data Analysis

## Overview

This Jupyter Notebook provides an analysis of Airbnb listings in Seattle, focusing on key insights such as average prices, factors influencing prices, and price comparisons between downtown and suburban areas. The notebook utilizes data from the Seattle Airbnb dataset and applies machine learning techniques to extract meaningful conclusions for both Airbnb hosts and travelers.

## Table of Contents
1. Introduction
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Importance
5. Price Comparisons

## 1. Introduction
The goal of this analysis is to:
- Identify the **average price** of renting an Airbnb in Seattle.
- Analyze **factors** that influence Airbnb listing prices.
- Compare prices between **downtown** and **suburban** Seattle areas.

## 2. Data Preprocessing
The dataset undergoes the following preprocessing steps:
- **Data cleaning**: Handling missing values and irrelevant features.
- **Feature encoding**: Converting categorical variables like 'bedrooms', 'bathrooms', 'beds', 'review_scores_rating', 'property_type', 'room_type', 'neighbourhood_group_cleansed'.

## 3. Exploratory Data Analysis (EDA)
Key visualizations and statistics are generated to understand the distribution of prices and other listing attributes:
- **Distribution of prices**: A graph shows the spread of Airbnb listing prices with the calculated average price of **$127.98** per night.
  
## 4. Feature Importance
Machine learning models are applied to determine the importance of different features that impact pricing. The top factors include:
- **Number of bedrooms** (importance score: 0.481)
- **Number of bathrooms** (importance score: 0.131)
- **Review scores** (importance score: 0.100)

A full table of feature importance is available for detailed analysis.

## 5. Price Comparisons
The analysis compares prices between two key regions:
- **Downtown Seattle**: Average price is **$154.41** per night.
- **Suburban Areas**: Average price is **$123.72** per night.

This section highlights the significant price difference between central and peripheral regions in Seattle.


## Dependencies
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## How to Run the Notebook
1. Clone the repository or download the notebook.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Launch the Jupyter Notebook.
4. Run the cells step-by-step to reproduce the analysis.
