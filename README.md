# EUR-to-INR-Currency-Price-Prediction
EUR to INR Currency Forecasting using Time Series (Facebook Prophet)

📌 Description:
This project aims to predict the future EUR to INR currency exchange rates using historical data and time series forecasting methods. It primarily utilizes the Facebook Prophet model for prediction and visualizes both historical and forecasted values.

📂 Dataset:
- File: EUR_INR Historical Data.csv

🧠 Methodology:
1. Data Preprocessing:
   - Cleaning and formatting the date
   - Handling missing values
   - Reversing data to chronological order
2. Model:
   - Facebook Prophet is used for time series forecasting
   - Supports daily, monthly, or user-defined date range predictions
3. Evaluation:
   - Mean Squared Error (MSE)
   - R-squared score (R²)
4. Visualization:
   - Forecast plot for user-specified dates or number of days
   - Actual vs predicted comparison chart

🔍 Features:
- Predict for custom number of days, months, or a specific future date
- Interactive user input for prediction range
- Forecast includes upper/lower bounds with confidence intervals
- Actual vs predicted graph for model evaluation

📦 Dependencies:
- Python 3.7+
- pandas
- matplotlib
- prophet (Facebook Prophet)
- scikit-learn (for evaluation metrics)

📈 Sample Output:
- Forecast for next 7 days
- Prediction for custom user date (e.g., '2025-08-01')
- R² Score: ~0.97
- MSE: ~0.45
- Graph comparing actual vs predicted rates

✅ Example Use Cases:
- Currency exchange rate prediction
- Financial forecasting
- AI-powered investment research
