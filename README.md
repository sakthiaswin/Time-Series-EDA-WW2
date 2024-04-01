# README.md

## Introduction
This repository contains code for analyzing World War II aerial bombing operations and weather conditions during the same period. The analysis is conducted using Python and various data visualization libraries. The data used in this analysis includes information on bombing missions, weather station locations, and weather conditions.

## Setup
This code is written in Python 3 and utilizes several libraries, including NumPy, pandas, Seaborn, Matplotlib, and Plotly. To run this code, you will need to have Python installed on your system along with the required libraries. You can install the necessary libraries using pip:


## Data Description
### Aerial Bombing Data
- **Mission Date:** Date of the mission
- **Theater of Operations:** Region where active military operations are in progress
- **Country:** Country that conducts the mission
- **Air Force:** Name or ID of the air force unit
- **Aircraft Series:** Model or type of aircraft
- **Takeoff Base:** Takeoff airport name
- **Takeoff Location:** Takeoff region
- **Takeoff Latitude:** Latitude of the takeoff region
- **Takeoff Longitude:** Longitude of the takeoff region
- **Target Country:** Target country of the mission
- **Target City:** Target city of the mission
- **Target Type:** Type of target
- **Target Industry:** Industry of the target
- **Target Priority:** Priority of the target
- **Target Latitude:** Latitude of the target
- **Target Longitude:** Longitude of the target

### Weather Condition Data
#### Weather Station Location
- **WBAN:** Weather station number
- **NAME:** Weather station name
- **STATE/COUNTRY ID:** Acronym of countries
- **Latitude:** Latitude of the weather station
- **Longitude:** Longitude of the weather station

#### Weather
- **STA:** Weather station number (WBAN)
- **Date:** Date of temperature measurement
- **MeanTemp:** Mean temperature

## Data Cleaning
The aerial bombing data includes NaN values, which are removed to enhance visualization. The weather condition data does not require cleaning.

## Data Visualization
The analysis includes various visualizations to understand the data:
- Number of countries involved in attacks
- Top target countries
- Top aircraft series
- Takeoff base locations
- Target locations
- Bombing paths
- Theater of Operations
- Weather station locations

## Time Series Analysis
The analysis includes time series analysis using ARIMA (AutoRegressive Integrated Moving Average) to predict future weather conditions.

## Forecasting
ARIMA models are used for time series forecasting, predicting future mean temperatures based on historical data.

## Conclusion
This repository provides insights into World War II aerial bombing operations and weather conditions during the same period, along with code for analysis and visualization.

