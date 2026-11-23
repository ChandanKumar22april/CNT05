Agricultural Commodity Price Forecasting and Market Analysis:-

Project Overview:-

This project focuses on analysing historical agricultural commodity prices in India using Descriptive Analytics.
The study examines the relationship between agricultural production, mandi arrivals, weather conditions, and trade patterns to understand variations in national agricultural commodity prices.
It also analyses price transmission from wholesale mandi markets to retail markets to understand how changes in mandi prices are reflected in retail prices.
The analysis aims to provide useful insights for agribusiness buyers regarding procurement decisions and price risk management.

Research Question:-

What are the historical patterns and trends in agricultural commodity prices in India, and how are these prices influenced by production, mandi arrivals, weather conditions, trade activities, and price transmission from mandi to retail markets?
Research Objectives
To analyse historical price trends of a selected agricultural commodity in India.

Research Objectives:-

1) To analyse historical price trends of a selected agricultural commodity in India.
2) To examine the relationship between agricultural production and commodity prices.
3) To study the impact of mandi arrivals on market price variations.
4) To understand how weather conditions and trade activities influence commodity prices.
5) To analyse price transmission from mandi markets to retail markets.
6) To identify historical price variations that may help agribusiness buyers make better procurement and hedging decisions.

Dataset
Dataset: Agricultural Commodity Price Dataset
The project uses historical agricultural market data for a selected commodity in India.
The dataset may contain the following variables:
Commodity Name
State Name
District Name
Market Name
Arrival Date
Minimum Price
Maximum Price
Modal Price
Production Quantity
Mandi Arrival Quantity
Retail Price
Weather Information
Import and Export Data
Multiple datasets may be combined to study the relationship between production, arrivals, weather, trade, and commodity prices.

Tools and Technologies:-

R Programming
RStudio
R Markdown
ggplot2
dplyr
readr
lubridate
janitor

Descriptive Analytics:-
The project uses statistical summaries, averages, percentages, frequency distributions, and graphical representations to understand historical agricultural commodity price patterns.
It examines historical price movements and the relationship between production, arrivals, weather, trade, and market prices.

Visualizations:-
The project includes four major visualizations:
1) Commodity Price Trends – Shows historical changes in the selected commodity's prices over time.
2) Production and Mandi Arrivals Analysis – Examines the relationship between production, mandi arrivals, and market prices.
3) Mandi vs Retail Price Comparison – Compares wholesale mandi prices with retail prices to understand price transmission.
4) Monthly Price Variation Analysis – Shows seasonal price variations across different months.
All visualizations are created using the ggplot2 package in R.

Project Structure:-

Project Structure

Agricultural-Price-Analysis/
│
├── data/
│   ├── commodity_prices.csv
│   ├── production.csv
│   ├── mandi_arrivals.csv
│   ├── retail_prices.csv
│   ├── weather.csv
│   └── trade_data.csv
│
├── outputs/
│   └── graphs/
│       ├── price_trends.png
│       ├── production_arrivals.png
│       ├── mandi_retail_comparison.png
│       └── monthly_variations.png
│
├── report/
│   └── Agricultural_Analysis.html
│
├── R/
│   └── Agricultural_Analysis.Rmd
│
├── Agricultural-Price-Analysis.Rproj
│
└── README.md

How to Run the Project?
Download or obtain the agricultural commodity price dataset.
Select an agricultural commodity for analysis.
Place the required datasets inside the data folder.
Open the project file using RStudio.
Open the R Markdown file.
Install the required R packages if they are not already installed.
Run or Knit the R Markdown file to generate the HTML report.

Project Location
India

Conclusion:-
This project demonstrates how descriptive analytics and R programming can be used to understand historical agricultural commodity price patterns in India.
The analysis provides insights into price trends, production levels, mandi arrivals, weather conditions, trade activities, and price differences between wholesale and retail markets.
These findings can help agribusiness buyers understand historical market behaviour and make informed procurement and hedging decisions.



