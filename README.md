# Time-Series-Predictions
Project done in the subject Time Series at Universidad de Alicante in 2025.

# Time-Series-Predictions

**Quarterly time series analysis of UK arrivals to Australia (1981-2011).**

**Note:** `.ipynb` notebook uses **R kernel** (not Python), implementing full time series analysis in R with `forecast::Arima`.

## Files

- `TimeSeriesProject.ipynb` - Complete analysis (R kernel): EDA, Box-Cox (log) transform, 25 SARIMA models, AIC/BIC + CV selection, diagnostics, forecasts
- `TimeSeriesProject.pdf` - Exported notebook report
- `Presentation.pdf` - Project presentation

## Key Results

**Best model:** ARIMA(0,1,1)×(0,1,1)<sub>4</sub> (log-transformed)  
**Metrics:** Best BIC + excellent MSE/MAE in cross-validation  
**Forecasts:** 12-step ahead with 80%/95% intervals