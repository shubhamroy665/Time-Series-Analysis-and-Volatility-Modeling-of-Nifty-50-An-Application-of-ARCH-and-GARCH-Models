# Time-Series Analysis and Volatility Modeling of Nifty 50: An Application of ARCH and GARCH Models

This project involves analyzing and modeling the time series data of Nifty 50 using various methods including ARIMA, ARMA, and GARCH models. The goal is to forecast stock prices and their volatility, and to visualize different statistical properties and forecasting results.

## Project Structure

The project includes the following components:

### 1. Data Preparation
- **[nifty.png](Images/nifty.png)**: Visualization of Nifty 50 data over time.
- **[nifty train test.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/nifty%20train%20test.png)**: Split of the data into training and testing sets.
- **[logreturn.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/logreturn.png)**: Logarithmic returns of Nifty 50.

### 2. Rolling Statistics
- **[Rolling Mean & Standard Deviation.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/Rolling%20Mean%20%26%20Standard%20Deviation.png)**: Rolling mean and standard deviation to assess stationarity.

### 3. Model Fitting and Forecasting
- **[ar forecasting.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/ar%20forcasting.png)**: Autoregressive (AR) model forecasting results.
- **[ma forecasting.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/ma%20forcasting.png)**: Moving Average (MA) model forecasting results.
- **[arma forecasting.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/arma%20forcasting.png)**: ARMA model forecasting results.
- **[arima(2,1,2).png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/arima(2,1,2).png)**: ARIMA model (2,1,2) forecasting results.
- **[arimazoom.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/arimazoom.png)**: Zoomed-in view of ARIMA model results.
- **[zoom ar.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/zoom%20ar.png)**: Zoomed-in view of AR model results.
- **[zoomma.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/zoomma.png)**: Zoomed-in view of MA model results.
- **[zoom arma.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/zoom%20arma.png)**: Zoomed-in view of ARMA model results.

### 4. Model Diagnostics
- **[afc.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/afc.png)**: Autocorrelation function (ACF) plot.
- **[niftyvar.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/niftyvar.png)**: Variance of Nifty 50 data over time.
- **[seasonality.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/seasonality.png)**: Seasonality in Nifty 50 data.

### 5. Volatility Modeling
- **[egarch.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/egarch.png)**: Exponential GARCH model results.
- **[gmplot.png](Time%20Series%20Analysis%20and%20Volatility%20Modeling%20of%20Nifty%2050%20An%20Application%20of%20ARCH%20and%20GARCH%20Models/Images/gmplot.png)**: GARCH model plot.

## Installation

To run the code in this project, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib statsmodels arch
