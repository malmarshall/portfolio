# Project 2 - Infectious Disease Forecasting (Time-Series)
#### Dataset: CDC FluView (Influenza-Like Illness)

## Goal: Forecast influenza activity using time-series models and analyze seasonal patterns. 

# Outline
1. Problem Definition
   - Why forecasting matters in public health
   - How forecasts support resources planning
3. Data Collection
   - Pull FluView data via CDC API or CSV
   - Select:
       - Region
       - Time period
       - ILI percentage
5. Exploratory Analysis
   - Plot time series
   - Idenitfy:
      - Seasonality
      - Trends
      - Anomalies
    - Decompose series (trend + seasonal + residual)
7. Data Preparation
   - Handle missing weeks
   - Convert to datetime index
   - Resample if needed
9. Modeling
    - Compare:
        - ARIMA/SARIMA
        - Prophet
        - LSTM (optional - advanced)
    - Evaluate:
       - RMSE
       - MAE
       - MAPE
11. Forecasting
    - Forecast next 12-52 weeks
    - Plot forecast vs. actual
    - Include confidence intervals
13. Interpretation
    - Discuss:
        - Peak timing
        - Seasonal patterns
        - Model limitations


## Deliverables:
- Notebook
- Forecast plots
- README with public health interpretation 
