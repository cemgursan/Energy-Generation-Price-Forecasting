# Smart Grid Optimization and Forecasting

This repository contains a comprehensive Jupyter Notebook project for optimizing and forecasting aspects of smart grids. The project demonstrates how to use multiple data sources, perform time-series analysis, and apply machine learning models to forecast solar irradiance, energy generation, and electricity prices.

## Overview

The project includes:
- **Data Collection & Processing:**  
  - Pulling solar radiation data from the NREL API for New York (using latitude and longitude).
  - Fetching electricity prices and consumption data from the EIA API.
- **Data Visualization:**  
  - Plotting solar irradiance and energy generation.
  - Visualizing forecasted electricity prices.
- **Time-Series Forecasting:**  
  - Using ARIMA for solar irradiance forecasting.
  - Forecasting electricity prices with SARIMA.
  - Leveraging XGBoost for additional electricity price forecasting.
- **Optimization Techniques:**  
  - Defining solar panel characteristics and calculating solar energy generation.
  - Comparing actual vs. forecasted energy production.

## Features

- **API Integration:**  
  - Retrieves solar data from the [NREL Solar Radiation API](https://developer.nrel.gov/docs/solar/solar-resource-v1/).
  - Fetches electricity data from the [EIA API v2](https://www.eia.gov/opendata/).
- **Data Analysis:**  
  - Utilizes `pandas` and `numpy` for data manipulation.
  - Visualizes data trends with `matplotlib` and `seaborn`.
- **Time-Series Forecasting:**  
  - Implements ARIMA/SARIMA models using `statsmodels` for solar and electricity data.
  - Uses `XGBoost` for advanced forecasting techniques.
- **Machine Learning & Deep Learning:**  
  - Incorporates libraries like `tensorflow` and `torch` (PyTorch) for potential future extensions.

## Installation

### Prerequisites

- [Python 3.8+](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/)
- Git

### Dependencies

Install the required Python packages using pip:

```bash
pip install requests pandas numpy matplotlib statsmodels seaborn xgboost prophet tensorflow torch scikit-learn scipy
