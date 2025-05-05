# R Data Science Projects

This repository contains several small R-based data science projects focused on modeling, forecasting, and visualization. Each project applies different techniques and packages for real-world analytical tasks.

## Projects Overview

### 1. Credit Risk Modeling

**File:** `credit risk modeling.R`  
This project uses logistic regression to model loan default prediction based on customer attributes from a bank loan dataset.

- **Key libraries:** `dplyr`, `ggplot2`, `caret`, `pROC`
- **Features:**
  - Data preprocessing and visualization
  - Logistic regression model training and evaluation
  - Confusion matrix and ROC curve plotting

### 2. Disease Spread Simulation

**File:** `Disease Spread Simulation.R`  
An interactive SIR (Susceptible-Infected-Recovered) model built using Shiny and `deSolve` to simulate the spread of a disease over time.

- **Key libraries:** `deSolve`, `ggplot2`, `reshape2`, `shiny`
- **Features:**
  - Interactive sliders for infection (β) and recovery (γ) rates
  - Real-time simulation and visualization of disease progression

### 3. Stock Price Analysis

**File:** `stock analysis.R`  
Analyzes stock trends using historical data fetched from Yahoo Finance. Visualizes price movement and moving averages.

- **Key libraries:** `quantmod`, `TTR`
- **Features:**
  - 20-day and 50-day Simple Moving Averages
  - Dynamic charting of stock prices (default: AAPL)

### 4. Time Series Forecasting

**File:** `time forecast.R`  
Performs ARIMA and ETS forecasting on the classic AirPassengers dataset.

- **Key libraries:** `forecast`, `ggplot2`, `tseries`, `Metrics`, `zoo`
- **Features:**
  - Stationarity testing and transformation
  - Model fitting and evaluation
  - Forecasting future passenger traffic with visualization
  - Model performance comparison using MAE and RMSE

## Visualizations

Project includes several plots such as:
- Income vs Loan Default histogram
- SIR model line graphs
- Stock price with moving averages
- ARIMA/ETS forecasts (log and original scale)

## Getting Started

1. **Install dependencies:**
   ```r
   install.packages(c("dplyr", "ggplot2", "caret", "pROC", "deSolve", "reshape2", "shiny", "quantmod", "TTR", "forecast", "tseries", "Metrics", "zoo"))
