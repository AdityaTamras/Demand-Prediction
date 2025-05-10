# Retail Store Demand Prediction

This project aims to use a machine learning model to forecast product demand in retail stores based on time series data.

# Dataset 
The dataset consists of the following attributes to train the model : 
1. The date of the sales record in date time format
2. The store ID where the sales was recorded
3. Item ID
4. Sales (The quantity of the specified item sold on the specified date in the store)

# Approach

1. Data Loading and Visualization to understand the data structure and identify any underlying patterns.

2. Extract relevant features from the date column and create additional numerical time duration features that are useful for model prediction

3. Lag Feature Generation to capture past sales patterns

4. Rolling mean features to smoothen sales data and capture trends

5. Exponential Weighted Moving Averages (EWMA). This gives more weight to recent sales data.

6. Implement Light Gradient Boosting Machine Algorithm and train the model on historical data

7. Evaluate model performance using SMAPE (Symmetric Mean Absolute Percentage Error) to gauge the accuracy of predictions

8. Predict sales values for new store-item combination and visualize forecasted sales as compared to actual sales.
