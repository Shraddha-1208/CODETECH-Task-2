- Name: Shraddha
- Company: CODTECH IT SOLUTIONS
- ID: CT08DS7177
- Domain: Data Analytics
- Duration: Aug to Sep 2024
- Mentor: SANTHOSH

  Overview of the Project
------------------------
Project: Bitcoin Price Prediction

Objective:The objective of this project is to preprocess Bitcoin price data, engineer features, resample data, scale features, and build a linear regression model to predict Bitcoin's closing price.

Key Activities:
- Data Preprocessing:Load the dataset, remove unnecessary columns and handle missing values, convert the 'date' column to a datetime format, sort by date, and convert the 'close', 'high', and 'low' columns to 
  numeric types.
- Feature Engineering:Calculate daily_return as the percentage change in closing price from one day to the next, price_range as the difference between the highest and lowest prices each day, and average_price as 
  the average of the high and low prices.
- Data Resampling:Resample the data from daily to weekly frequency, aggregating key metrics such as open price, high price, low price, close price, volume, daily return, price range, and average price.
- Feature Scaling:Scale the numeric features ('open', 'high', 'low', 'close', 'volume') to a range between 0 and 1 using MinMaxScaler.
- Model Building:Prepare features (X) and target (y), split the data into training and testing sets, train a linear regression model, and evaluate it using the R-squared value while printing the model's intercept 
  and coefficients.

Dataset: https://github.com/Shraddha-1208/CODETECH-Task-2/blob/main/new.csv

Technologies Used:
- Python: The primary programming language for data analysis.
- pandas: Data manipulation and analysis.
- numpy: Numerical operations.
- matplotlib: Static visualizations.
- seaborn: Statistical data visualization.
- sklearn: For scaling features and building the linear regression model.
