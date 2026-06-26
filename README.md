# Time-Series-project
# Forecasting Amazon (AMZN) Stock Prices Using Time Series Analysis
## Overview:
This project focuses on forecasting Amazon (AMZN) stock prices using traditional statistical techniques and deep learning models. Historical stock market data from Yahoo Finance (2010–2020) was collected, preprocessed, and used to compare forecasting performance across multiple models.
## Dataset:
- Source: Yahoo Finance
- Period: January 2010 – December 2020
- Target Variable: Closing Price
## Data Preprocessing:
- Handled missing values
- Applied logarithmic transformation
- Performed first-order differencing
- Normalized data using MinMaxScaler
- Split dataset into 80% training and 20% testing
## Models Implemented:
-ARMA (AutoRegressive Moving Average)
-LSTM (Long Short-Term Memory)
-GAN-assisted Time Series Augmentation
## Evaluation Metrics:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score
## Results:
The LSTM model outperformed the traditional ARMA model, with an R² score of about 95.5%. Additionally, the project investigated the use of a GAN-generated synthetic dataset to assess the effects of the GAN on forecast accuracy.
## Tech Stack:
Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
