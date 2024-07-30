# Time-Series Analysis and Volatility Modeling of Nifty 50: An Application of ARCH and GARCH Models

This project involves analyzing and modeling the time series data of Nifty 50 using various methods including ARIMA, ARMA, and GARCH models. The goal is to forecast stock prices and their volatility, and to visualize different statistical properties and forecasting results.

## Project Structure

The project includes the following components:

### 1. Data Preparation
- **nifty.png**: Visualization of Nifty 50 data over time.
- **nifty train test.png**: Split of the data into training and testing sets.
- **logreturn.png**: Logarithmic returns of Nifty 50.

### 2. Rolling Statistics
- **Rolling Mean & Standard Deviation.png**: Rolling mean and standard deviation to assess stationarity.

### 3. Model Fitting and Forecasting
- **ar forecasting.png**: Autoregressive (AR) model forecasting results.
- **ma forecasting.png**: Moving Average (MA) model forecasting results.
- **arma forecasting.png**: ARMA model forecasting results.
- **arima(2,1,2).png**: ARIMA model (2,1,2) forecasting results.
- **arimazoom.png**: Zoomed-in view of ARIMA model results.
- **zoom ar.png**: Zoomed-in view of AR model results.
- **zoomma.png**: Zoomed-in view of MA model results.
- **zoom arma.png**: Zoomed-in view of ARMA model results.

### 4. Model Diagnostics
- **afc.png**: Autocorrelation function (ACF) plot.
- **niftyvar.png**: Variance of Nifty 50 data over time.
- **seasonality.png**: Seasonality in Nifty 50 data.

### 5. Volatility Modeling
- **egarch.png**: Exponential GARCH model results.
- **gmplot.png**: GARCH model plot.

## Installation

To run the code in this project, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib statsmodels arch
