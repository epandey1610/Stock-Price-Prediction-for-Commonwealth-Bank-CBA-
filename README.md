# Stock-Price-Prediction-for-Commonwealth-Bank-CBA-
This project focuses on predicting the stock price of Commonwealth Bank (CBA) using machine learning. The goal is to explore time-series forecasting techniques, evaluate different models, and understand the challenges of working with financial data.

The requirements.txt file includes: pandas,numpy,yfinance,scikit-learn,xgboost and matplotlib

# Key Learnings-

1) Overfitting is a Real Challenge

2) Complex models like Random Forest and XGBoost can easily overfit, especially with limited data. Regularization (e.g., limiting tree depth) is essential.

# Feature Engineering Matters

1) Technical indicators like moving averages and volatility added valuable information to the models.

2) Time-Series Data Requires Special Handling

# Chronological train-test splits are crucial to avoid data leakage.

1) Simplicity Can Be Powerful

2) Linear Regression performed surprisingly well, highlighting the importance of starting with simple models.

# Future Improvements

1) Incorporate external data (e.g., macroeconomic indicators, news sentiment).
2) Experiment with advanced models like LSTMs for time-series forecasting.
3) Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
