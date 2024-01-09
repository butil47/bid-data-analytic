# bid-data-analytic
## Author

Melat Solomon Ayele

## movie big data analysis

## Overview

This project explores a movie dataset to discover trends, patterns, and insights related to movie genre, release year, runtime, popularity, and revenue. It involves data cleaning, feature engineering, analysis and conclusion of exploratory data.

## Dataset

- Source: [https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv]

## Key Steps

1.**Data Discovery:**
Examine the structure and summary statistics of a data set.
Identify missing values ​​and outliers..

2.**Data Cleaning:**

- Handle missing values ​​by deleting rows with missing data.
- Correct outliers using Z-score calculation.

  3.**Feature engineering:**

-Creating new features

- Release year from release date
  -Coded separately by genre
  Revenue /budget ratio
- Average vote popularity and interaction

  4.**Exploratory data analysis:**
  Visualize distributions and relationships between variables using Seaborn and Matplotlib.

- Test descriptive statistics.

  5.**Results or conclusion:**
  Identify popular genres over the years.

- Analyze runtime distribution and genre relationships.
- Explore rates revenue on budget.

- Most popular genres each year
- Number of films in different performance categories
- Number of films for each genre
- Most popular genre Overall

## Dependencies

- pandas
- scipy.stats
- seaborn
- matplotlib

## Repository Contents

-`tmdb-movies.csv`: The original movie dataset.

- Big_Data_Analytic.ipynb
- `README.md`: This file .

## Instructions for Running the Analysis

1. Download the dataset from the provided link.
2. Run on google colab.
