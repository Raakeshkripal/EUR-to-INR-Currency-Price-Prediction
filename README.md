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

🔧 TECHNICAL TERMS EXPLAINED:
📈 1. Time Series
Definition: A series of data points indexed in time order.
Example in this project: Historical EUR to INR exchange rates over days or months.

🔮 2. Forecasting
Definition: Predicting future values based on past data patterns.
In context: Predicting the future value of EUR to INR using past exchange rate data.

🧠 3. Facebook Prophet
Definition: A time series forecasting tool developed by Facebook (now Meta).
Why use it? 
- Works well with daily seasonality and irregular time series.
- Automatically handles holidays, trends, and outliers.
In this project: Used to forecast future currency exchange rates.

📊 4. MSE (Mean Squared Error)
Definition: A metric that tells us how close predictions are to the actual values.
Formula: 
    MSE = (1/n) * Σ(actualᵢ - predictedᵢ)²
Interpretation: Lower MSE means better model accuracy.

📈 5. R² Score (R-squared)
Definition: A metric that shows how much variance in the actual data is explained by the model.
Range: From 0 to 1.
Interpretation:
    1.0 → perfect prediction
    0.0 → model fails to explain any variance
In your project: An R² score closer to 1 indicates high prediction accuracy.

📅 6. Date Indexing
Definition: Using dates as the index for time series data.
Why it matters: Time-based models like Prophet require data with a time index to track trends over time.

🔁 7. Chronological Order
Definition: Sorting data from the oldest date to the most recent.
Why it’s used: Forecasting models need data to be in order to learn trends properly.

📥 8. User Input Features
Definition: Dynamic options where the user provides values.
In this project:
- Choose number of days to predict
- Enter a specific future date
- Select a custom date range for plotting

📉 9. Prediction Interval (Upper & Lower Bound)
Definition: A range around the predicted value that shows possible variation.
Example: If predicted = 95, lower = 93, upper = 97 → the actual value is likely between 93 and 97.

📊 10. Actual vs Predicted Graph
Definition: A visual comparison of real (historical) data and forecasted values.
Why it’s useful: Helps to quickly see how well the model performs.

