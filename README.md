# applied-analytics-sp500-bitcoin
Applied Analytics project analyzing S&amp;P 500 and Bitcoin data (2019–2024). Includes descriptive statistics, trends over 5 years, correlation analysis, and normality checks. Visualizations created using R and ggplot2 to tell a clear story of financial trends and relationships.

Applied Analytics Project: S&P 500 vs Bitcoin
## Overview
This project explores the relationship between the S&P 500 and Bitcoin over the period 2019–2024. Using open financial data, we analyze trends, calculate descriptive statistics, and examine correlations to understand the dynamics of traditional and cryptocurrency markets.
Problem Statement
Compare S&P 500 and Bitcoin price trends over five years.
Calculate descriptive statistics (mean, median, mode, range, standard deviation, etc.) for both datasets.
Examine correlations between S&P 500 and Bitcoin prices over time.
Assess whether the datasets follow a normal distribution.
Key Insights
Trends: S&P 500 shows steady growth; Bitcoin is highly volatile.
Statistics: Bitcoin exhibits higher variability and extreme values compared to S&P 500.
Correlation: Moderate to strong positive correlation observed in six-month intervals.
Normality: S&P 500 data is closer to normal distribution; Bitcoin shows slight right-skew.
Visualizations
Area plots for S&P 500 and Bitcoin trends.
Comparative bar charts of descriptive statistics.
Correlation line plots over six-month intervals.
Scatter plots with smooth trends highlighting relationships.
Histograms assessing data distribution.
Technologies Used
R: Data cleaning, analysis, and visualization
ggplot2: Trend and distribution plots
dplyr: Data manipulation
tidyr: Data reshaping
Repository Structure
data/ – Raw and processed CSV files for S&P 500 and Bitcoin
scripts/ – R scripts for analysis and visualization
README.md – Project overview and instructions
Data Sources
S&P 500 data – Yahoo Finance CSV
Bitcoin (BTC-USD) data – Yahoo Finance CSV
How to Use
Clone this repository.
Open the R scripts in RStudio.
Run the scripts to reproduce all analyses and visualizations.
