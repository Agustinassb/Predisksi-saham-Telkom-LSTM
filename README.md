# Stock Price Prediction Using LSTM
This repository features a comprehensive data science project that utilizes Long Short-Term Memory (LSTM) networks to predict stock prices based on historical data. Developed as part of the AI Mastery Program under the Merdeka Belajar Kampus Merdeka (MBKM) initiative by Orbit Future Academy, this project showcases skills in data preprocessing, analysis, visualization, and predictive modeling.


## Overview
This project focuses on predicting the closing prices of Telkom Indonesia (TLKM.JK) stocks using historical data from 2017-01-02 to 2022-09-01. The prediction is performed with an LSTM neural network, a deep learning model particularly suited for time-series forecasting.
The project demonstrates expertise in:
- Data preprocessing and handling of real-world datasets.
- Applying machine learning and deep learning models.
- Generating actionable insights from data.

## Dataset Description
The dataset contains daily stock prices of Telkom Indonesia (TLKM.JK) with the following attributes:

- Date: The date of the record.
- Open: The price at the market opening.
- High: The highest price of the stock during the day.
- Low: The lowest price of the stock during the day.
- Close: The price at the market closing (target for prediction).
- Adj Close: Adjusted closing price.
- Volume: Total volume of stocks traded during the day.

Dataset Summary:
- Total Records: 1422 entries
- Date Range: 2017-01-02 to 2022-09-01

## Tech
The project uses the following technologies and tools:
- Python: The primary programming language used for data analysis and model development.
- Jupyter Notebook: For interactive code development and visualization.
- TensorFlow/Keras: For building and training the LSTM model.
- NumPy: For numerical computations.
- Pandas: For data handling and manipulation.
- Matplotlib and Seaborn: For data visualization.
- Sklearn: For preprocessing and evaluation metrics.

## Workflow
The project follows a structured pipeline:
1. Data Loading and Cleaning
- Handling missing values.
- Normalizing data for compatibility with the LSTM model.
2. Exploratory Data Analysis (EDA)
- Visualizing stock price trends over time.
-Understanding seasonality and volatility in stock prices.
3. Feature Engineering
- Selecting key features like Close prices for modeling.
- Splitting data into training and testing sets (e.g., 80%-20%).
4. Model Building
- Implementing an LSTM model using Keras/TensorFlow.
- Configuring the architecture:
- Input layers for time-series data.
- LSTM layers with memory cells for sequential learning.
- Dense layers for output predictions.
5. Model Training and Evaluation
- Training the model with normalized data.
- Evaluating performance using metrics like Mean Squared Error (MSE) and - - - visual comparison of actual vs. predicted prices.
6. Prediction
- Using the trained model to predict future stock prices.


## Results and Insights
Key Results:
- The LSTM model successfully learned trends in the historical stock data, with predictions closely matching the actual closing prices.
- Predictions were normalized and rescaled to original price ranges for comparison.
- Example predictions:
    - Actual Price: 4500 | Predicted Price: 4523
    - Actual Price: 3980 | Predicted Price: 4012



 
