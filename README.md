# Unemployment-trend-analysis
## Overview
This project analyzes global unemployment trends using historical data from 1991 to 2021. The analysis includes descriptive statistics, time-series visualizations, and predictive modeling techniques to understand factors affecting unemployment rates across countries.
## Background
This analysis is based on a dataset capturing unemployment rates across different countries. The objective is to explore global economic trends, understand regional disparities, and assess the impact of major global events, such as the 2008 financial crisis and COVID-19 pandemic, on employment. This project is essential for policymakers, businesses, and international organizations to devise strategies for economic growth, workforce development, and crisis management.
## Data Source
The dataset used for this analysis is sourced from the World Bank Unemployment Data, available at:
https://www.kaggle.com/datasets/shivavashishtha/world-bank-unemployment-data
### Data Dictionary
• Country Name: Name of the country
• Country Code: Three-letter country code
• Years (1991 to 2021): Unemployment rates for each year, represented as a percentage of the total labor force
## Data Analysis
### Descriptive Statistics
- Computing the average global unemployment rate for 2021.
- Identifying the country with the highest unemployment rate in 2021.
- Listing the top 5 countries with the lowest average unemployment rate from 1991 to 2021.
- Detecting outliers in the dataset that indicate unusual spikes or drops in unemployment rates.

### Machine Learning Models
- Building a regression model to predict unemployment rates.
- Visualizing actual vs. predicted unemployment rates.
- Implementing a classification model to categorize unemployment trends.
- Applying K-means clustering to group countries based on unemployment trends.
Key Findings & Conclusions
- The average global unemployment rate in 2021 was identified, with significant variations across regions.
- Highest unemployment rates were observed in specific countries, highlighting economic challenges.
- The 2008 financial crisis led to a noticeable spike in global unemployment rates, with a recovery trend observed in the following years.
- COVID-19 had a major impact on employment in 2020-2021, causing a sharp increase in unemployment due to lockdowns and economic disruptions.
- Some regions displayed stable employment trends, indicating resilience in their job markets.
- The regression model provided reasonably accurate predictions, helping to anticipate future unemployment trends.
- K-means clustering successfully grouped countries based on unemployment characteristics, revealing distinct employment patterns.
## Repository Structure
```
- Unemployment_trend_analysis.ipynb  # Jupyter Notebook with all analyses
- data/                              # Folder containing dataset(s)
- images/                            # Visualizations generated during analysis
- models/                            # Saved machine learning models
- README.md                          # Project documentation
```
## Requirements & Setup
To run this notebook, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

## Run the Jupyter Notebook using:
```bash
jupyter notebook Unemployment_trend_analysis.ipynb
```
## Future Enhancements
- Implementing deep learning models for more advanced unemployment prediction.
- Expanding the dataset to include GDP, inflation, and other macroeconomic indicators.
- Developing an interactive dashboard for real-time unemployment trend analysis.
- Investigating external factors such as oil prices, geopolitical events, and educational levels that may influence unemployment rates.
- Assessing the effectiveness of unemployment policies implemented in various countries.

