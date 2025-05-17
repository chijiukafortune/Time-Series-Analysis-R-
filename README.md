# Time-Series-Analysis-R-
Industry project analysing UK online debit card spending (2020–2025) using SARIMA, VAR, Holt-Winters, and LSTM. Integrated fuel prices to assess economic impact. Delivered forecasting model and insights for business decision-making.


# ⏳ Time Series Forecasting Project (R)

## Overview

This repository contains an end-to-end time series analysis and forecasting project focused on UK online debit card spending patterns and their relationship with fuel prices.

The analysis covers:
- **Consumer Spending** via debit card transactions
- **Exogenous Variables** including ULSP and ULSD fuel prices
- **Forecasting Models**: SARIMA, SARIMAX, VAR, Holt-Winters, and LSTM (Keras)

## Objectives

- Detect trends and seasonality in consumer spending
- Examine the causal impact of fuel prices on spending using Granger causality
- Forecast future values with traditional and deep learning models
- Evaluate model performance using RMSE and visualisation

## Technologies

- **Language**: R
- **Libraries**:
  - Time Series: `forecast`, `tseries`, `zoo`, `MTS`, `vars`, `prophet`
  - Machine Learning: `caret`, `randomForest`, `e1071`
  - Deep Learning: `keras`, `tensorflow`
  - Visualisation: `ggplot2`, `corrplot`
  - Data Handling: `dplyr`, `tidyverse`, `readxl`, `readr`, `lubridate`

## Files

- `Cleaned_Anachal_Report.Rmd`: Clean and documented R Markdown file with all analysis
- `spendings_dataset.xlsx`: Dataset for online debit card transactions
- `road_fuel_prices_240325.csv`: Dataset for fuel prices
- `README.md`: Project documentation

## How to Run

1. Clone the repo
2. Open `Cleaned_Anachal_Report.Rmd` in RStudio
3. Ensure the required libraries are installed
4. Knit the file to HTML or run step-by-step

## Author

**Fortune** | University of Bolton | May 2025
