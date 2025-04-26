# Analysis of Video Game Sales Record Dataset

## Overview

This project analyzes a dataset of video game sales records to understand the factors that contribute to a game's success. The analysis explores genre preferences across different regions, the relationship between game ratings and sales, and the feasibility of predicting sales using machine learning models.

## Key Findings

* **Genre Preferences:** North America and Europe have similar preferences, while Japan has unique tastes. The "Misc" genre is widely popular, and platform games maintain their appeal.
* **Ratings and Sales:** High critic and user scores are strongly correlated with higher global sales.
* **Sales Prediction:** Linear and Polynomial Regression models show limited predictive power, suggesting the influence of external factors.
* **Sales Category Prediction:** A Logistic Regression model achieves good accuracy in predicting sales categories (Low, Medium, High).

## Data

The analysis uses the "Video_Games.csv" dataset from Kaggle, containing information about game names, platforms, release years, genres, publishers, sales figures, ratings, and user reviews.

## Methodology

* **Data Cleaning:** Handling missing values and data preprocessing.
* **Genre Analysis:** Calculating average sales by genre and region.
* **Clustering:** Grouping games based on critic score, user score, and global sales.
* **Regression Models:** Building Linear and Polynomial Regression models for sales prediction.
* **Logistic Regression:** Adapting Logistic Regression to predict sales categories.

## Insights

The analysis provides valuable insights for game developers and publishers, including:

* Understanding regional genre preferences.
* The importance of high game ratings.
* The limitations of current predictive models.
* The potential for using machine learning to aid business decisions.

## How to Use

1. Download the "Video_Games.csv" dataset and place it in the same directory as this notebook.
2. Install the required libraries: pandas, scikit-learn, matplotlib.
3. Run the notebook cells sequentially to execute the analysis.

