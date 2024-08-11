# Rice Sustainability Project

## Overview
The Rice Sustainability Project is an initiative aimed at addressing critical challenges related to rice security, loss, and waste in Asian countries. Given that rice is a staple food for over 3.5 billion people and provides 20% of the world’s dietary energy supply, it is crucial to ensure its sustainability. This project utilizes data science techniques to analyze and model various aspects of the rice supply chain, with the goal of reducing loss and waste, improving food security, and mitigating greenhouse gas (GHG) emissions.

## Problem Statement
1. **Rice Security**  
   How can we increase rice supply in a way that is economically accessible and nutritionally sufficient for well-being?

2. **Rice Loss & Waste**  
   How can we reduce rice loss and waste along the supply chain to sustain food supply?

3. **GHG Emission**  
   What is the impact of the rice supply chain on the environment, particularly in terms of greenhouse gas emissions?

## Hypothesis
Implementing targeted measures to minimize rice loss and waste in the rice supply chain will lead to a significant reduction in greenhouse gas (GHG) emissions and enhance rice security.

## Project Framework

### Data Pipeline
Our approach follows the **SCRUB-OBTAIN-EXPLORE-MODEL-INTERPRET** framework, which includes:

- **SCRUB:** Handling missing values, normalizing numerical features, dealing with duplicated data, encoding categorical variables, and feature engineering.
- **OBTAIN:** Collecting data from various sources, including FAOSTAT databases covering crops, food balances, climate change, food loss, and food security indicators.
- **EXPLORE:** Performing exploratory data analysis (EDA) to calculate key metrics such as Loss Percentage and Self-Sufficiency Ratio (SSR).
- **MODEL:** Developing predictive models using Ridge Regression and ARIMA to forecast rice production trends, self-sufficiency ratios, loss percentages, and GHG emissions.
- **INTERPRET:** Analyzing results from EDA and predictive modeling to gain insights, draw conclusions, and visualize the impact of findings.

### Data Sources
We use data from the following sources:

- **FAOSTAT Crops and Livestock Products**
- **FAOSTAT Food Balances**
- **FAOSTAT Climate Change: Agrifood Systems Emissions**
- **FAOSTAT Food Loss and Waste Database**
- **FAOSTAT Suite of Food Security Indicators**

## Predictive Modeling
We developed the following models:

1. **Ridge Regression Models** to predict:
   - Total rice production trends over the years.
   - Average self-sufficiency ratio (SSR) trends.

2. **ARIMA Models** to predict:
   - Loss percentage for each activity in the food supply chain.
   - Total losses in each country over the next 10 years.
   - Mean GHG emissions trends for the top 5 items in Asia.

## Dashboard
For an interactive view of the project’s findings and predictions, please visit the [Rice Sustainability Project Dashboard](https://xxinjie.shinyapps.io/Rice_Analysis_Prediction/).
