# Time-Series Analysis and Volatility Modeling of Nifty 50: An Application of ARCH and GARCH Models

This project involves analyzing and modeling the time series data of Nifty 50 using various methods including ARIMA, ARMA, and GARCH models. The goal is to forecast stock prices and their volatility, and to visualize different statistical properties and forecasting results.

## Project Structure

The project includes the following components:

### 1. Data Preparation
- **![Nifty 50 Data](Images/nifty.png)**: Visualization of Nifty 50 data over time.
- **![Train Test Split](Images/nifty%20train%20test.png)**: Split of the data into training and testing sets.
- **![Logarithmic Returns](Images/logreturn.png)**: Logarithmic returns of Nifty 50.

### 2. Rolling Statistics
- **![Rolling Mean & Standard Deviation](Images/Rolling%20Mean%20%26%20Standard%20Deviation.png)**: Rolling mean and standard deviation to assess stationarity.

### 3. Model Fitting and Forecasting
- **![AR Forecasting](Images/ar%20forcasting.png)**: Autoregressive (AR) model forecasting results.
- **![MA Forecasting](Images/ma%20forcasting.png)**: Moving Average (MA) model forecasting results.
- **![ARMA Forecasting](Images/arma%20forcasting.png)**: ARMA model forecasting results.
- **![ARIMA(2,1,2) Forecasting](Images/arima(2,1,2).png)**: ARIMA model (2,1,2) forecasting results.
- **![ARIMA Zoom](Images/arimazoom.png)**: Zoomed-in view of ARIMA model results.
- **![AR Zoom](Images/zoom%20ar.png)**: Zoomed-in view of AR model results.
- **![MA Zoom](Images/zoomma.png)**: Zoomed-in view of MA model results.
- **![ARMA Zoom](Images/zoom%20arma.png)**: Zoomed-in view of ARMA model results.

### 4. Model Diagnostics
- **![ACF](Images/afc.png)**: Autocorrelation function (ACF) plot.
- **![Variance](Images/niftyvar.png)**: Variance of Nifty 50 data over time.
- **![Seasonality](Images/seasonality.png)**: Seasonality in Nifty 50 data.

### 5. Volatility Modeling
- **![EGARCH](Images/egarch.png)**: Exponential GARCH model results.
- **![GARCH Plot](Images/gmplot.png)**: GARCH model plot.

## Installation

To run the code in this project, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib statsmodels arch
