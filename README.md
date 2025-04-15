# Stock-Price-Forecasting-of-U.S.-Technological-Companies-Using-Machine-Learning-and-Deep-Learning
Forecasting stock prices of major U.S. tech companies using machine learning and deep learning models like ARIMA, XGBoost, LSTM, and Prophet for accurate financial prediction and investment insights.

## Project Overview
This project explores stock price forecasting in the U.S. technology sector using a combination of machine learning and deep learning techniques. It focuses on five leading companies—Apple, Google, Microsoft, Amazon, and Meta—whose stocks have played a critical role in shaping global financial trends. The aim is to develop accurate predictive models that empower investors to make informed decisions. The project compares classical time series models like ARIMA with advanced approaches such as XGBoost and LSTM, delivering a comprehensive evaluation of their effectiveness in financial forecasting.

## Objective
The primary goals of this project were:

To collect and preprocess stock market data from multiple financial sources including Yahoo Finance and Google Finance. To investigate the relevance of key variables such as the day of the week, NASDAQ index, and historical trends in stock movement. To apply and compare traditional (ARIMA), machine learning (XGBoost), and deep learning (LSTM, Facebook Prophet) forecasting models. To evaluate model performance using metrics such as RMSE, MAE, and MAPE. To analyze patterns across companies and determine which model provides the most accurate predictions in a real-world test scenario.

### Key Features
1. Data Collection and Cleaning
Stock data from April 2014 to December 2022 was collected for five major U.S. tech companies. Missing dates due to non-trading days were handled using forward fill techniques, and features were engineered to capture temporal trends.

2. Feature Engineering
Derived features such as day of the week, day of year, quarter, and change in price were used to enrich the models. Predictors included open, high, low, volume, NASDAQ index, and derived change values.

3. Modeling Techniques
Applied ARIMA for traditional time series forecasting, XGBoost for feature-rich machine learning prediction, and LSTM and Facebook Prophet for capturing sequential dependencies and nonlinear patterns in stock price movements.

4. Evaluation Metrics
Forecasting accuracy was validated using RMSE, MSE, MAE, and MAPE. LSTM showed superior performance in three of five stocks, while XGBoost performed best for the remaining two.

5. Visual Forecasting
Visualizations included time-series plots for predicted vs. actual stock movements, demonstrating each model's effectiveness in trend prediction and directionality over a 365-day test period.


### Summary of Achievements
This project implemented a robust stock price forecasting pipeline combining time series models, machine learning, and deep learning techniques. It successfully identified LSTM and XGBoost as the best-performing models across different stocks. By focusing on temporal and market-based variables, the models captured essential stock behaviors and provided a reliable tool for financial forecasting in the technology sector.

## Conclusion
The project demonstrates the potential of advanced computational methods in the high-stakes world of stock price forecasting. Deep learning models like LSTM excelled in sequential pattern recognition, while XGBoost effectively utilized a broader set of engineered features. These models offer scalable, data-driven approaches that can help investors and analysts anticipate market behavior and make more informed decisions in the ever-evolving tech-driven financial landscape.


