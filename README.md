# Applied Analytics Project: S&P 500 vs Bitcoin
## Overview
This project explores the relationship between the S&P 500 and Bitcoin over the period 2019–2024. Using open financial data, we analyze trends, calculate descriptive statistics, and examine correlations to understand the dynamics of traditional and cryptocurrency markets.
## Problem Statement
Compare S&P 500 and Bitcoin price trends over five years.<br>
Calculate descriptive statistics (mean, median, mode, range, standard deviation, etc.) for both datasets.<br>
Examine correlations between S&P 500 and Bitcoin prices over time.<br>
Assess whether the datasets follow a normal distribution.
## Key Insights
Trends: S&P 500 shows steady growth; Bitcoin is highly volatile.<br>
Statistics: Bitcoin exhibits higher variability and extreme values compared to S&P 500.<br>
Correlation: Moderate to strong positive correlation observed in six-month intervals.<br>
Normality: S&P 500 data is closer to normal distribution; Bitcoin shows slight right-skew.
## Visualizations
Area plots for S&P 500 and Bitcoin trends.<br>
Comparative bar charts of descriptive statistics.<br>
Correlation line plots over six-month intervals.<br>
Scatter plots with smooth trends highlighting relationships.<br>
Histograms assessing data distribution.
## Technologies Used
R: Data cleaning, analysis, and visualization<br>
ggplot2: Trend and distribution plots<br>
dplyr: Data manipulation<br>
tidyr: Data reshaping<br>
## Repository Structure
data/ – Raw and processed CSV files for S&P 500 and Bitcoin<br>
scripts/ – R scripts for analysis and visualization<br>
README.md – Project overview and instructions<br>
## Data Sources
S&P 500 data – Yahoo Finance CSV<br>
Bitcoin (BTC-USD) data – Yahoo Finance CSV<br>
## How to Use
Clone this repository.<br>
Open the R scripts in RStudio.<br>
Run the scripts to reproduce all analyses and visualizations.
