## Yash Bank Stock Price Prediction
This project focuses on building and evaluating a machine learning regression model to predict the monthly closing price of Yes Bank stock. The analysis uses historical stock data to identify key relationships between price variables and build a reliable predictive model.

## 🛠️ Project Details
* Project Type: Regression 
* Project Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Scikit-learn, Seaborn

## 🚀 Key Findings
* **Data Trends**: A long-term time series analysis of the stock price reveals a significant downtrend and high volatility, particularly after 2018.
* **Outliers**: Outliers were identified in the data, which often represent real-world market events, so they were not removed. Instead, new features were engineered to capture price range and change.
* **Feature Importance**: In the final model, the Low price for the month was found to be the most influential feature for predicting the Close price.
* **Model Performance**: The chosen Ridge Regression model achieved an R² score of 0.99 on the test set, with a Mean Absolute Error (MAE) of 5.81. This means the model's predictions are, on average, off by about 5.81 units from the actual closing price.
