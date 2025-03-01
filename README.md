# Time-Series-Analysis
## Overview
This academic project covers exploratory data analysis and forecasts the stock prices of Tesla by applying various machine learning models. The models used in this study include: 
(1)Naive Method 
(2)Exponential Smoothing 
(3)Simple Average 
(4)Moving Average 
(5)ARIMA (Autoregressive Integrated Moving Average) 
(6)SARIMA (Seasonal Autoregressive Integrated Moving Average) 
The performances of these machine learning models are compared using error metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). The models have undergone various parameter tunings to get the best performance.  
## Dataset
The dataset used for this project consists of Tesla stock price of five years period, retrieved from NSDAQ stock platform. 
## Objectives
Perform exploratory data analysis (EDA) to understand trends, seasonality, and patterns in the dataset. 
Apply various forecasting models to predict Tesla's stock prices. 
Evaluate the performance of each model using appropriate statistical metrics. 
Compare model performance and select the best-suited model for time-series forecasting. 
## Implementation
The project is implemented in Python, utilizing libraries such as: 
pandas for data manipulation 
numpy for numerical computations 
matplotlib & seaborn for visualization 
statsmodels for statistical modeling 
## Results & Findings
The exploratory data analysis revealed trends and seasonality in Tesla's stock prices. 
Each model demonstrated varying levels of accuracy in forecasting future prices. 
The performance comparison identified the most effective model based on error metrics. 
SARIMA and Holt's Winter showed better accuracy compared to simpler models like Naive and Moving Average. 
