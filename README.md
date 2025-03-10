# Intellihack_Pandas_and_Pythons_Task_4
# Stock Price Prediction Challenge

## Overview
This project explores a stock price prediction challenge using machine learning. The objective is to develop a model capable of accurately predicting stock prices five days into the future. 

The project follows a structured approach, utilizing exploratory data analysis (EDA) to identify predictive features, including various technical indicators. Multiple models were trained and evaluated, including:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- LSTM
- GRU
- ARIMA

## Approach
The stock price prediction challenge involves several key steps:

### 1. Data Analysis
- Conducted Exploratory Data Analysis (EDA) to uncover patterns and trends in historical stock data.
- Identified key factors influencing stock price movements.

### 2. Feature Engineering
- Created meaningful features from time-series data, including technical indicators and lagged values.
- Incorporated moving averages, daily returns, rolling volatility, and seasonal decomposition.

### 3. Model Development
- Implemented and trained six different models: Linear Regression, Random Forest Regressor, XGBoost Regressor, LSTM, GRU, and ARIMA.
- Applied data preprocessing techniques such as scaling, sequence creation, and cross-validation.

### 4. Model Evaluation
- Used statistical metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to compare model performance.
- Conducted simulated trading performance analysis to assess practical usability.

### 5. Presentation
- Clearly documented methodology, feature importance, and model limitations.
- Visualized key insights and trends through plots and reports.

## Key Techniques & Considerations
### Data Processing & Feature Engineering
- **Moving Averages:** Computed Simple Moving Averages (SMA) and Exponential Moving Averages (EMA) to identify trends.
- **Daily Returns Analysis:** Analyzed the distribution of daily returns to assess stock stability.
- **Rolling Volatility Analysis:** Measured volatility to quantify risk and price fluctuations.
- **Seasonal Decomposition Analysis:** Identified recurring patterns in stock prices.
- **Feature Selection:** Used time-based and price-based features, technical indicators, and market sentiment analysis.
- **Data Preprocessing:** 
  - Date conversion
  - Column removal
  - Handling infinite values
  - Missing value treatment (interpolation and filling NaNs)
  - Target variable creation

### Model Training & Selection
- **Training Pipeline:**
  - Implemented Linear Regression, Random Forest Regressor, XGBoost Regressor, LSTM, GRU, and ARIMA models.
  - Applied appropriate data scaling and sequence creation techniques.
  - Used **TimeSeriesSplit (5-fold cross-validation)** for XGBoost to improve generalization on time-dependent data.
- **Model Selection:**
  - Linear Regression was chosen for its consistent and reliable predictive capabilities across training and validation datasets.
  - ARIMA demonstrated lower error metrics during training but was less robust across datasets.

## Conclusion
This project demonstrates a comprehensive approach to stock price prediction using machine learning. The combination of exploratory data analysis, feature engineering, and diverse model training enables insights into stock price movements and predictive performance.

---

### Future Enhancements
- Incorporating sentiment analysis from financial news and social media.
- Experimenting with ensemble learning techniques for improved accuracy.
- Testing additional deep learning architectures such as Transformer-based models.

Feel free to explore the repository, and contributions are welcome! 🎯
