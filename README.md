# Data-Driven Insights: Taxi Demand Forecasting for Sweet Lift

This project focuses on building a time series forecasting model to predict the number of taxi orders for the next hour at airports for Sweet Lift Taxi. Accurate short-term demand forecasting enables the company to attract more drivers during peak hours and improve service availability.

The analysis emphasizes both predictive accuracy and proper time series data preparation.

# Objective

To test the following hypothesis:

Hourly taxi demand can be accurately forecasted using historical order data, achieving a Root Mean Squared Error (RMSE) of 48 or lower on the test dataset.

# 🛠️ Technologies Used

Python: Pandas, NumPy, Scikit-learn

Statsmodels / Gradient Boosting Models: Time series modeling

Jupyter Notebook: Interactive environment for analysis and experimentation

CSV Dataset: Historical taxi order data

# Key Steps
# Data Description

Loaded historical taxi order data indexed by time.

Identified the target variable (num_orders).

# Data Resampling and Preparation

Resampled the data into hourly intervals.

Ensured consistent time steps for time series modeling.

Created lag features and rolling statistics where appropriate.

# Exploratory Data Analysis

Analyzed trends, seasonality, and cyclical patterns.

Examined daily and weekly demand fluctuations.

# Model Development

Trained multiple forecasting models using different algorithms and hyperparameters.

Split the dataset into training and test sets, with 10% reserved for testing.

Tuned models to improve predictive accuracy.

# Model Evaluation

Evaluated model performance on the test dataset using RMSE.

Compared results across models to select the best-performing approach.

# Results

The analysis shows that:

Taxi demand exhibits strong temporal patterns that can be captured through time series modeling.

Feature engineering significantly improves forecast accuracy.

The final model achieved an RMSE below 48 on the test set.

Accurate demand forecasting enables better driver allocation during peak hours.

These results demonstrate that Sweet Lift Taxi can leverage time series forecasting to optimize operations and improve customer experience.
