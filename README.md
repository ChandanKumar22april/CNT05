# Agriculture Commodity Price Forecasting

**Project:** CNT-05 – Country Agricultural Commodity Price Forecasting  
**Author:** Chandan Kumar  
**Date:** November 2026

## 1. Introduction

Agricultural commodity prices fluctuate due to changes in production, market arrivals, weather conditions, supply and demand, and international trade.

This project analyses historical agricultural commodity prices and develops a data-driven forecasting approach to estimate future prices. It also examines mandi-to-retail price transmission and explores procurement and hedging implications for agribusiness buyers.

## 2. Objectives

- Analyse historical prices of agricultural commodities.
- Compare prices across different states and agricultural markets.
- Study the relationship between production and mandi arrivals.
- Examine the influence of weather conditions on prices.
- Analyse import and export patterns.
- Examine wholesale-to-retail price transmission.
- Develop a forecasting model for national-level commodity prices.
- Provide procurement and hedging insights for agribusiness buyers.

## 3. Commodities Covered

The project considers five agricultural commodities:

1. Onion
2. Tomato
3. Wheat
4. Rice
5. Potato

## 4. Dataset Description

The dataset contains 1,800 observations and 19 variables, covering January 2023 to December 2025.

It includes:

- Commodity and state information
- District and market details
- Arrival dates
- Minimum, maximum and modal prices
- Production and mandi arrivals
- Retail prices
- Weather conditions
- Temperature and rainfall
- Import and export quantities

**Data coverage:** 10 agricultural markets across 6 states.

**Important limitation:** The national monthly price series is calculated using arrivals-weighted average prices from the available markets. It is a national-level proxy and should not be interpreted as an official all-India market price.

## 5. Technologies Used

- R Programming
- RStudio
- R Markdown
- Tidyverse
- dplyr
- ggplot2
- lubridate
- forecast
- reshape2

## 6. Project Methodology

The project follows these steps:

1. Data import and initial inspection
2. Data cleaning and preparation
3. Descriptive statistical analysis
4. Commodity-wise price analysis
5. Monthly price trend analysis
6. Seasonal price analysis
7. State-wise price analysis
8. Correlation analysis
9. National monthly price aggregation
10. Training and testing data preparation
11. Forecasting model development and comparison
12. Forecast evaluation and interpretation
13. Procurement and hedging implications

## 7. Forecasting Models

The project compares the following time-series forecasting models:

- Naive Forecast
- Seasonal Naive Forecast
- ARIMA (AutoRegressive Integrated Moving Average)

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The final model selection is based on the evaluation results.

## 8. Project Structure

```text
CNT05-Project/
│
├── Agriculture_Commodity_Price_Forecasting.Rmd
├── agricultural_commodity_price_dataset.csv
├── Agriculture_Commodity_Price_Forecasting.html
├── README.md
└── .gitignore
```

## 9. How to Run the Project

1. Install R and RStudio.
2. Download or clone this repository.
3. Open the `.Rmd` file in RStudio.
4. Install the required packages if they are not already installed.
5. Update the dataset file path if necessary.
6. Click the **Knit** button to generate the HTML report.

## 10. Expected Outcome

The project aims to:

- Understand historical agricultural commodity price movements.
- Identify seasonal and geographical price variations.
- Compare forecasting model performance.
- Estimate future monthly commodity prices.
- Support data-driven procurement and hedging decisions.

## 11. Project Status

**Status:** Forecasting model development in progress.

Model evaluation results and final forecast interpretations will be added after completing the forecasting analysis.

## 12. Author

**Chandan Kumar**  
CNT-05 – Agriculture Commodity Price Forecasting
