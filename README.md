# Traffic Density Prediction with EDA and LSTM

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.12%2B-orange)

Predict urban traffic density using Long Short-Term Memory (LSTM) networks, combined with exploratory data analysis (EDA) to uncover patterns in time-series traffic data.

## 📌 Project Overview

**Objective**: Forecast traffic density (vehicles/hour) at key urban intersections using historical sensor data.  
**Key Workflow**:
1. Exploratory analysis of traffic patterns
2. Time-series feature engineering
3. LSTM-based density prediction
4. Model interpretation and deployment recommendations

**Key Questions**:
- How do traffic patterns vary by time of day/day of week?
- What external factors (weather, events) correlate with traffic spikes?
- How far into the future can we reliably predict congestion?

## 🛠️ Features

### EDA Components
- Hourly/daily/weekly traffic pattern visualizations
- Correlation analysis with weather and event data
- Missing data imputation strategies
- Seasonality and trend decomposition

### LSTM Model
- Sliding window time-series preprocessing
- Multi-variable LSTM architecture
- Hyperparameter tuning (epochs, lookback window, layers)
- Performance metrics: MAE, RMSE, R² score

### Visualization Tools
- Interactive Plotly timeseries plots
- Heatmaps of congestion hotspots
- Prediction vs actual comparison graphs

