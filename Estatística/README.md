# Chess Data Analysis: Exploring Player Performance and Metrics

## Overview

This project focuses on statistical analysis and feature engineering using a dataset of chess games, dados_chess_age.csv. The goal is to explore player performance, identify trends, and extract meaningful insights from historical game data. The project demonstrates key data science techniques including data preprocessing, visualization, and analysis of player-specific metrics.

---

## Key Features
### 📊 Data Preprocessing

Handling missing or inconsistent values (e.g., replacing ? with NaN and converting data types).
Transforming string representations of numerical lists into usable formats.
Feature engineering for metrics such as Elo rating differences and game results.

### 📈 Exploratory Data Analysis

Visualization of distributions (histograms, boxplots) for metrics like rounds, results, and Elo differences.
Correlation heatmaps to identify relationships between features.
Time-series plots to analyze individual player performance trends over time.

### 🧩 Advanced Analytics

Subsetting the data for analysis of "White" and "Black" players separately.
Calculating and visualizing performance differences between players.
Investigating metrics such as Average CP Loss, Elo differences, and match outcomes.

### 🛠️ Custom Functions and Iterative Insights

Functions for cleaning and transforming data, such as calculating the mean of a list of values.
Extracting key metrics like the start date of each player’s career.

---

## Tools and Technologies

Python Libraries: pandas, numpy, seaborn, and matplotlib.
Jupyter Notebook: For interactive coding and visualization.

---

## Getting Started
Clone the repository and navigate to the project folder:

    git clone <repo-link>
    cd <repo-name>

Install required dependencies:

    pip install -r requirements.txt

Open the Jupyter Notebook to explore the analysis:

    jupyter notebook Untitled.ipynb

---

## Future Enhancements

Incorporate machine learning models to predict match outcomes.
Expand the dataset to include more games and player statistics.
Perform deeper analysis on the impact of age and experience on performance.
