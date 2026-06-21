# Simple Linear Regression - Marketing ROI Analysis

This repository contains a data science project focused on evaluating the relationship between various marketing channels (TV, Radio, Social Media) and sales performance using Simple Linear Regression.

## Project Overview
The goal of this analysis is to identify which marketing channel has the strongest measurable impact on sales and to provide budget allocation recommendations based on statistical insights.

## Methodology
1. **Data Cleaning:** Handled missing values by dropping incomplete rows to ensure data quality.
2. **Exploratory Data Analysis (EDA):** Built a correlation matrix and scatter plots to determine the best predictor for sales.
3. **Model Building:** Constructed an Ordinary Least Squares (OLS) regression model using the strongest predictor.
4. **Model Diagnostics:** Implemented linearity checks, residual plots, QQ-plots, and formal statistical tests (Shapiro-Wilk for normality and Breusch-Pagan for homoscedasticity).

## Technologies Used
* Python 3
* Pandas & NumPy (Data Manipulation)
* Matplotlib & Seaborn (Data Visualization)
* Statsmodels & SciPy (Statistical Modeling & Hypothesis Testing)

## Key Recommendation
Based on the correlation analysis, the marketing channel with the strongest positive relationship to sales was selected as the optimal channel for maximum ROI. The final recommendation is to allocate more marketing budget to this channel due to its statistically significant and measurable impact on overall sales output.
