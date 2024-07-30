# Time Series Modelling for Real Estate Values

## Overview
This project aims to empower real estate investors with sophisticated time series models using Zillow's dataset. By leveraging advanced forecasting techniques, the project provides accurate insights for strategic decision-making in real estate investments.

## Contributors
- Carol Mundia
- Crystal Wanjiru
- Ian Nzangi
- Pascalia Maiga

## Project Outline
1. Introduction
2. Problem Statement
3. Objectives
4. Data Understanding
5. Data Preparation
6. Exploratory Data Analysis (EDA)
7. Modelling
8. Recommendations
9. Conclusions

## Introduction
The goal of this project is to provide investors with a time series model to forecast real estate values using historical data from Zillow. This enables investors to make informed decisions on potential investment opportunities.

## Problem Statement
Real estate investment requires meticulous analysis and strategic decision-making. This project aims to identify the top zip codes offering promising investment opportunities by leveraging historical data from Zillow Research.

## Objectives
1. Identify the top 5 zip codes and states with the best investment potential.
2. Analyze historical real estate value data to understand patterns over various time intervals (monthly, quarterly, semi-annual, and annual).
3. Create a time series model to predict future real estate values.

## Data Understanding
- Dataset contains 14723 rows and 272 columns.
- Columns include RegionID, RegionName (zip code), State, City, SizeRank, and house values for each region.
- Date range: April 1996 to April 2018.

## Data Preparation
- Removed missing values, reducing data to 13680 rows.
- No duplicate values, but outliers were retained as recorded events.
- Created two data frames: one for EDA and another for time series analysis and modeling.
- Added a "Returns on Investment" column.

## Exploratory Data Analysis (EDA)
- Histogram showed normally distributed average return on investment (ROI).
- Most regions had an average ROI between 0.02 to 0.06.
- States with the highest number of houses: California, New York, Texas, Pennsylvania.
- Top zip codes for ROI: 11211, 11222, 11216 (Brooklyn, NY), 7302 (Jersey City, NJ), 11930 (Amagansett, NY).
- States with highest ROI: New York, New Jersey, Delaware, South Dakota, California.
- Overall upward trend in house values, except for a fall between 2006 and 2013 due to the 2008 recession.

## Modelling
### ARIMA Models
- 4 ARIMA models were tested.
- Model with the least error: 4th ARIMA model.
  - MAE: 84.47
  - RMSE: 117.55

### Prophet Models
- 3 Prophet models were tested.
- Model with the least error: 3rd Prophet model.
  - MAE: 86.22
  - RMSE: 121.87

### Model Comparison
- The 4th ARIMA model performed best overall.

## Recommendations
### Real Estate Investment
- Invest in real estate due to an upward trend in house values.
### States and Regions
- Recommended states: New York, New Jersey, Delaware, South Dakota, California.
- Top zip codes: 11211, 11222, 11216 (Brooklyn, NY), 7302 (Jersey City, NJ), 11930 (Amagansett, NY).
### Forecasting Model
- Use the developed model to forecast future real estate values to mitigate risks.

## Conclusion
- A predictive model was built to assist investors in making informed real estate investment decisions in the United States.
### Next Steps
- Collect more real estate value data to improve model accuracy.
- Continuously train the model for better predictive results.

## Contact
For further information, please contact any of the team members listed above.
