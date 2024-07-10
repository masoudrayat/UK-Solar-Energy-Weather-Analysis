
# README

## Project Overview

The aim of this project is to conduct a correlation analysis between weather data and solar panel energy generation in a location in the UK. Additionally, a machine learning prediction model is developed using a 2-week weather forecast to estimate the solar panel generation at the community centre.

This repository includes three Jupyter notebooks that perform data analytics and predictions on weather data and solar panel power generation. The notebooks utilise a public API to retrieve weather data and forecast information for analysis.

## Technologies Used

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.21-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3-green.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4-yellow.svg)
![Requests](https://img.shields.io/badge/Requests-2.25-red.svg)


## Notebooks Description

### Two_Week_Forecast.ipynb

This notebook focuses on retrieving forecast weather data from a public API for further analysis. The steps in this notebook include:

- **Retrieving Forecast Data:** Using the public API to obtain forecast weather data.
- **Forecast Analysis:** Performing analysis on the forecasted weather data.
- **Pattern Exploration:** Exploring patterns or trends in the forecasted weather.
- **Impact Analysis:** Analyzing how forecasted weather may impact power generation from the solar panel.

### Historic_Weather_Correlation.ipynb

In this notebook, weather data is retrieved from a public API and cleaned for further analysis. The steps involved are:

- **Retrieving Weather Data:** Using a public API to gather historical weather data.
- **Cleaning Data:** Removing any inconsistencies or missing values from the weather data.
- **Extracting Power Generation Data:** Obtaining power generation data from the solar panel at the community centre.
- **Relationship Analysis:** Analyzing the relationship between weather data and power generation.
- **Correlation Analysis:** Finding correlations between weather variables and power generation.

### Weather_Solar_Prediction.ipynb

This notebook covers the overall project, including the correlation analysis and the development of a machine learning model to make predictions based on the four weather variables most correlated with solar panel generation. The steps in this notebook are as follows:

- **Multicollinearity Check:** Identifying potential issues caused by high correlations between predictor variables.
- **Principal Component Analysis (PCA):** Addressing multicollinearity issues by transforming correlated variables into a new set of uncorrelated variables called principal components.
- **Multiple Linear Regression Model:** Building a regression model using the transformed principal components as predictors.
- **Goodness of Fit:** Assessing the model's fit using the R-squared value, which measures the proportion of variance in solar power generation explained by the predictors.
- **Cross-Validation:** Evaluating the model's performance and generalisation ability.


## Conclusion

This project provides a comprehensive analysis of the correlation between weather data and solar panel energy generation. By utilising machine learning models, it also predicts future solar panel generation based on weather forecasts. The findings and models developed in this project can help optimise solar energy utilisation in the community centre.

