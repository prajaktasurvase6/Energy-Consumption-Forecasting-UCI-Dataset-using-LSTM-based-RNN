# Energy Consumption Forecasting using LSTM-based RNN

This project focuses on time series forecasting of household energy consumption using the **UCI Household Power Consumption Dataset**. A deep learning model using a **Bidirectional LSTM-based Recurrent Neural Network** (RNN) has been implemented for this purpose.

## Problem Statement
Forecast hourly energy consumption by analyzing trends and seasonality in the dataset, enabling smarter energy management strategies.

##  Report
The project report can be found here:  
[`Energy_Consumption_Forecasting_(UCI_Dataset)_using_LSTM_based_RNN.pdf`](Energy_Consumption_Forecasting_(UCI_Dataset)_using_LSTM_based_RNN.pdf)

##  Dataset
The dataset is sourced from the UCI Machine Learning Repository:  
[UCI Household Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)

##  Model Overview
- **Model**: Bidirectional LSTM with Dropout, BatchNorm
- **Metrics**: MSE, R²
- **Features**: Global power metrics + engineered time features

##  Technologies
- Python
- TensorFlow/Keras
- Pandas, Matplotlib, Seaborn
- Scikit-learn

##  Results
- Model achieved an R² score > 0.5 on validation data
- Demonstrated seasonality and trend learning via LSTM structure

