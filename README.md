# Capstone-Project---Initial-Report-and-EDA
Berkeley ML-AI - July 22, 2026, by Timothy Vermette

## Project Overview
### Housing Affordability Across 100 Major United States Metrpolitan Areas
Housing affordability has become an increasingly important economic and social issue in the United States. The purpose of this project is to explore factors that are most strongly associated with the ability to achieve the “American Dream” of home ownership. Using data from Zillow and the U.S. Census Bureau, this analysis will explore relationships among home values, median household income, educational attainment, and population, across the top 100 largest metropolitan areas in the U.S. The goal is to obtain a better understanding of the factors associated with house prices and affordability, to explore population trends, and identify the metropolitan areas where homeownership is more or less attainable.

# Research Question
What economic factors (home prices, median income, educational attainment) influence American households’ ability to buy a home, and what US cities have become the least and most attainable and populated?

## Link to Capstone Project Jupyter Notebook on GitHub
https://github.com/t-vermette/Capstone-Project---Initial-Report-and-EDA/blob/main/Capstone_Project.ipynb

## Link to Accompanying Data Exploration Jupyter Notebook on GitHub
https://github.com/t-vermette/Capstone-Project---Initial-Report-and-EDA/blob/main/Capstone%20Dataset%20Exploration.ipynb

## Data Sources
- Zillow Home Value Index (ZHVI)
- U.S. Census Bureau ACS 5-Year Estimates
  - Median Household Income
  - Population
  - Educational Attainment

## Methodology
This phase of the project consisted of:
1. Collecting Zillow and U.S. Census Bureau data.
2. Cleaning and merging multiple public datasets.
3. Engineering affordability-related features.
4. Performing exploratory data analysis.
5. Building and evaluating a baseline Multiple Linear Regression model.

## Current Progress (Phase 1)
- Collected and merged data from Zillow and the U.S. Census Bureau
- Built a unified analytical dataset for the Top 100 U.S. metropolitan areas
- Performed exploratory data analysis (EDA)
- Engineered affordability metrics, including Price-to-Income Ratio
- Developed and evaluated a baseline Multiple Linear Regression model

## Preliminary Findings
- Median household income exhibited the strongest positive relationship with metropolitan home values.
- Home values varied substantially across metropolitan areas despite similar income levels.
- The baseline Linear Regression model explained approximately 80% of the variation in home values (R² = 0.804).
- Educational attainment demonstrated evidence of multicollinearity with income, suggesting additional modeling will be required.

## Future Work
The Final Capstone Project will:
- Incorporate historical data from 2010 and 2015 using equivalent datasets from U.S. Census Bureau
- Analyze changes in affordability over time
- Compare Linear Regression with Ridge and Lasso Regression
- Explore additional features related to housing affordability
- Develop a final predictive model and business recommendations

