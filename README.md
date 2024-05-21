# Climate

The goal of this analysis is to understand the temporal patterns in sea surface temperature (SST) data from the [North Pacific](https://raw.githubusercontent.com/Parsar22/Climate/main/Climate/north_pacific.csv) region. By applying various time series and spectral analysis techniques, we aim to identify dominant frequencies and trends, assess the spectral content, and explore relationships with other meteorological variables such as wind speed.


## Requirements
Software: Python 3+ pandas (for data manipulation) NumPy (for numerical computations) Seaborn or Matplotlib (for visualizations) scikit-learn (for machine learning models)

## Analysis
Analysis
Time Series Analysis
The initial step in the analysis involved plotting the SST time series to visualize the overall trend and variability. This plot revealed significant short-term and long-term fluctuations in SST values, indicating both seasonal and decadal patterns.

Spectral Analysis
To further investigate the periodic components of the SST data, Welch's method was applied for spectral analysis. This technique helps identify dominant frequencies in the data by estimating the power spectral density (PSD). The PSD plot highlighted significant recurring patterns in the SST data, with higher power at lower frequencies suggesting that long-term trends are a major component of SST variations.

Low-Pass Filtering
A Butterworth low-pass filter was designed and applied to the SST data to highlight long-term trends by removing high-frequency components. This filtering process allowed us to visualize the underlying decadal variations more clearly, providing a smoother representation of the SST time series.

Linear Regression Analysis
A linear regression model was fitted to the filtered SST data to quantify the long-term trend. The analysis revealed an estimated warming rate of 0.0040°C per year, indicating a gradual increase in SST over the analyzed period. This positive trend is consistent with global warming observations.

### Forecasting
To forecast future SST values, a multi-lag linear regression model was employed. This model uses past SST values (lags) to predict future values. The model's predictions for the next decade were compared to the observed values, with the forecast indicating that the mean SST in the North Pacific will remain relatively stable with minor fluctuations.

Author
Parsa Rahimiderimi

License
This project is open source and can be used with references
