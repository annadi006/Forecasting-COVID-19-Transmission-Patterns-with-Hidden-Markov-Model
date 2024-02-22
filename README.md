COVID-19 Time Series Analysis with ARIMA Model
This code performs time series analysis on COVID-19 data using the ARIMA (AutoRegressive Integrated Moving Average) model. The analysis includes data preprocessing, stationarity tests, model training, and forecasting.

Prerequisites
Google Colab Account: Ensure you have a Google Colab account as this code is designed to run on this platform.

GITHUB LINK:-https://github.com/annadi006/Forecasting-COVID-19-Transmission-Patterns-with-Hidden-Markov-Model/tree/main

Dataset: The code requires the COVID-19 dataset (time_series_covid19_confirmed_US.csv). Upload this dataset to your Google Drive.

Steps to Run
1)Open Google Colab:

2)Open Google Colab in your web browser.
Mount Google Drive:

3)Run the first code cell to mount your Google Drive. This will prompt you to authenticate and provide a link to enter an authentication code.
Upload Dataset:

4)Upload the COVID-19 dataset (time_series_covid19_confirmed_US.csv) to your Google Drive.
Run the Code:

5)Run each code cell in the provided Jupyter notebook on Google Colab. You can do this by clicking the play button on each cell or by selecting "Runtime" and then "Run all."
Data Preprocessing:

6)The code performs data preprocessing, including dropping unnecessary columns and creating a new DataFrame with aggregated daily COVID-19 cases.
Stationarity Test:

7)Check the stationarity of the time series using the Augmented Dickey-Fuller test.
ARIMA Model:

8)Find the best ARIMA model parameters using a grid search based on the Akaike Information Criterion (AIC).
Train the Model:

9)Train the ARIMA model on the training dataset.
Forecasting:

10)Use the trained ARIMA model to make forecasts for different time horizons (50, 100, 200 steps).
Error Metrics:

11)Evaluate the accuracy of the forecasts using various error metrics,
 including Mean Absolute Error (MAE),
 Mean Squared Error (MSE),
 Root Mean Squared Error (RMSE),
 and Mean Absolute Percentage Error (MAPE).

12)Log-Likelihood:
Calculate the log-likelihoods for different forecast horizons and based on residuals.


Note
Ensure the dataset is available in the specified Google Drive path.
The code uses the statsmodels library for ARIMA modeling and various metrics from sklearn.metrics.

File Structure
time_series_covid19_confirmed_US.csv: Dataset containing COVID-19 confirmed cases.
ARIMA_Time_Series_Analysis.ipynb: Jupyter notebook with the code for time series analysis with the ARIMA model.
