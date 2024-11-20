# ML-Based-Drought-Forecasting-model-Utilizing-Metrological-Data
## Introduction:
This project seeks to harness the power of ML to deliver reliable, data-driven drought forecasts.
By integrating meteorological data and leveraging models like ARIMA for time-series forecasting and Temporal Convolutional Networks (TCN) for deep learning, this project aims to provide a robust framework for predicting droughts with greater accuracy and timeliness.
With applications in agriculture, water management, and policy-making, the model is designed to support informed decision-making and proactive resource management, ultimately contributing to resilience against climate impacts.
## Proposed Model:
The proposed system is a machine learning-based drought prediction model that combines time series forecasting and a Temporal Convolutional Network (TCN) to predict drought conditions. 
It first utilizes the ARIMA model to forecast future precipitation and temperature values based on historical time series data. 
These forecasted values are then used as inputs to the TCN model, which is designed to capture temporal dependencies in the data.
The TCN model is trained to classify drought conditions by analyzing past weather data, with a binary output indicating the likelihood of a drought event.

In file named Project1_Final_1, I trained the dataset with already existing models(both with sampling and without sampling) to compare them to my newly developed Arima-TCN Hybrid model.
The second file named Project1_Final_2 contain my Arima-TCN hybrid model.
