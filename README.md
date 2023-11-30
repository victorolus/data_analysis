# Movie Data Analysis and Visualization

## Overview

This project involves the analysis and visualization of movie data using Python's pandas, numpy, seaborn, and matplotlib libraries. The dataset, sourced from a CSV file, includes information about movies such as budget, gross earnings, score, and company details.

- Link to file: https://www.kaggle.com/datasets/danielgrijalvas/movies/

## Setup

1. Ensure you have the required Python packages installed:
   - pandas
   - numpy
   - seaborn
   - matplotlib

2. Clone the repository to your local machine.

3. Execute the Python script to perform the analysis and generate visualizations.

## Code Structure

- **Importing Packages:**
  - Pandas, NumPy, Seaborn, and Matplotlib are imported for data manipulation and visualization.

- **Reading Data:**
  - The dataset is read from a CSV file named `movies.csv` using pandas.

- **Data Exploration:**
  - Missing data is checked for each column in the dataset.
  - Data types of 'budget' and 'gross' columns are converted to 'int64'.

- **Data Analysis and Visualization:**
  - Boxplot to check for outliers in the 'gross' column.
  - Scatter plot and regression plot of 'budget' vs 'gross'.
  - Correlation analysis among numeric columns.
  - Heatmap visualization of the correlation matrix.
  - Identification of weak to strong correlation pairs.
  - Grouping by company and calculating the mean revenue for each.
  - Bar chart visualizing the top companies by mean revenue.

## Results and Visualizations

- **Budget vs Gross Earnings:**
  - Scatter and regression plots show the relationship between movie budgets and gross earnings.

- **Correlation Matrix:**
  - Heatmap visualizes the correlation matrix among numeric features.

- **Top Companies by Mean Revenue:**
  - Bar chart showcases the top companies by mean revenue.

## Usage

1. Run the Python script to analyze and visualize the movie data.
2. Explore the generated plots for insights into movie budget, gross earnings, and company performance.

