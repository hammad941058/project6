Sales Prediction Using LSTM and Web-Based Deployment
Goal: To predict sales using historical data and provide an interactive web-based prediction service.
Exploratory Data Analysis (EDA) for insights.
LSTM-based regression model for time series sales prediction.
Interactive web application for real-time and batch predictions.
Deployment of the application for end-user accessibility.
Store Data: Information about stores (e.g., type, location, competition).
Train Data: Historical sales data.
Test Data: Features without sales values.
DayOfWeek, Promo, StateHoliday, SchoolHoliday, CompetitionDistance.
Target Variable: Sales (in the train dataset).
Pie chart showing data distribution by store type.
Bar plot of average sales by day of the week.
Histogram showing the distribution of sales.
Heatmap highlighting correlations between features and sales.
Line chart showing monthly sales trends
Scatter plot of sales vs. competition distance
Model Used: Long Short-Term Memory (LSTM) Neural Network
Data Preprocessing:
	Handling missing values, feature scaling, and sliding window transformations.
Model Architecture:
	2 LSTM layers, dropout for regularization, dense output layer.
Training:
	Optimizer: Adam | Loss: Mean Squared Error (MSE).
Architecture diagram of the LSTM model.
Training RMSE: 2472.95
Validation MSE: 0.0513
Validation RMSE: 0.0513
Validation R²: 0.9485
Residual Analysis:
	Histogram of residuals showing minimal bias
Visualization:
	Line plot comparing actual vs. predicted sales.
Input Fields: Store ID, Date, Promo details.
Batch Predictions: CSV upload feature
Predicted vs. Actual Sales.
Time-series sales trends
Hosted locally. Preparing for Heroku deployment
Sales Trends: Line plot showing sales over time.
Predicted vs. Actual Sales: Scatter plot with a diagonal line for perfect predictions
Experiment with advanced architectures and hyperparameters
Include weather data, economic indicators, and regional events.
Migrate app to Heroku or AWS.
Scale for real-time predictions

