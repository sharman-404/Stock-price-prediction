# Hybrid-Stock-price-prediction-System
LSTM + XGBoost Ensemble Model for Financial Time-Series Forecasting

Project Summary

This project builds a hybrid stock price prediction system that forecasts the daily closing price of Tata Motors using:

1. Long Short-Term Memory (LSTM) – for sequential time-series learning

2. XGBoost Regression – for structured feature modeling

3. Weighted Ensemble Strategy – to combine strengths of both models

The system improves forecasting stability in highly volatile financial markets by integrating technical indicators + deep learning + gradient boosting.


Why This Project Stands Out

1. Combines Machine Learning + Deep Learning
2. Implements advanced feature engineering (financial indicators)
3. Applies hybrid ensemble strategy
4. Uses real NSE stock market data
5. Evaluated with industry-standard metrics (RMSE, MAE, MAPE)
6. Designed with scalability in mind (multi-stock & real-time ready)


Model Performance
 Metric  Hybrid Model 
 ------  ------------ 
 RMSE    13.16        
 MAE     10.53        
 MAPE    1.5%  
 The hybrid model outperformed standalone LSTM and XGBoost models, reducing overall prediction error.


Technical Architecture
1. Data Pipeline

  a. Historical stock data collection

  b. Data cleaning & preprocessing

  c. Technical indicator computation

  d.Feature engineering (including lag features)

  e. Normalization & reshaping

2. Modeling Layer

  a. LSTM (Sequential Learning)

  b. XGBoost (Tree-Based Boosting)

  c. Hybrid Weighted Averaging

3. Evaluation

  a. RMSE

  b. MAE

  c. MAPE


Technical Indicators Engineered

  1. SMA (Simple Moving Average)

  2. EMA (Exponential Moving Average)

  3. RSI (Relative Strength Index)

  4. MACD

  5. Bollinger Bands

  6. OBV (On Balance Volume)

  7. ATR (Average True Range)

  8. VWAP



Tech Stack
 1. Programming
  Python

2. Data & Visualization

  Pandas

  NumPy

  Matplotlib

  Seaborn

3. Machine Learning

  XGBoost

  Scikit-learn

  Deep Learning

  TensorFlow

  Keras (LSTM Networks)

4. Environment

  Jupyter Notebook
 




Challenges Solved
Problem	                    Approach
1. Stock volatility	        Added technical indicators + lag features
2. LSTM overfitting	        Early stopping + tuning
3. Feature imbalance        Feature selection & scaling
4. Model instability	      Hybrid ensemble strategy


Future Scope

1. Multi-stock forecasting

2. Integration of news sentiment analysis

3. Real-time dashboard deployment (Streamlit/Flask)

4. Transformer-based models

5. Long-term multi-step forecasting


Key Skills Demonstrated

1. Time-Series Forecasting

2. Financial Feature Engineering

3. Deep Learning (LSTM)

4. Gradient Boosting (XGBoost)

5. Model Evaluation & Error Analysis

6. Hybrid Ensemble Modeling

7. Data Visualization




Recruiter Note

This project demonstrates practical application of AI in financial markets by:

1. Translating raw market data into predictive insights

2. Combining deep learning and boosting techniques

3. Designing an ensemble system for improved robustness

4. Evaluating models using quantitative performance metrics

5. It reflects strong understanding of machine learning pipelines, deep learning architectures, and real-world data challenges.


Author

Sharmanpreet Singh
B.Tech – Computer Science & Engineering
Amity University Punjab
