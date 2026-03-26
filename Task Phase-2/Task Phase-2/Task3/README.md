Task objective:
Energy Consumption Time Series Forecasting
My Approach:
)Load dataset into jupyter download from kaggle(household_power_consumption.txt)
2)Data cleaning such as checking duplicate values and Null values
3)Preprocessing data such as converting all numeric columns to float It ensures your dataset is ready for the rigorous mathematical requirements of machine learning models and Engineer time-based features This function transforms a simple Time Series (a list of dates and power values) into a tabular dataset that a Machine Learning model can actually understand..
4)Exploratory Data Analysis (EDA):
4.1)Time series Visualization
4.2)Visualization of Energy Consumption by Day of Week
4.3)Visualization of Energy Consumption by Hour
4.4)Visualization of Energy Consumption by Day of Week
4.5) Distribution of Energy Consumption
5)Train different model such as ARIMA, Prophet, and XGBoost models
6)Plot actual vs. forecasted energy usage for visualization showing different model perfomance

Results and findings:
1)XGBoost: Highest accuracy (lowest MAE/RMSE). Successfully identified non-linear spikes through lag features.
2)Prophet: Best at identifying seasonality. Easily handled daily and weekly cycles with minimal adjustments required.
3)ARIMA: Least performing model. Faced difficulty in handling 'double seasonality' - both daily and weekly cycles at once.