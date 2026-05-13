# Task 2: Stock Price Prediction using Machine Learning

## Overview

This project predicts the next day's closing stock price using historical stock market data fetched from Yahoo Finance. A Random Forest Regressor model is trained using stock features such as Open, High, Low, and Volume to estimate future closing prices.



# Objective

The main objective of this project is to:

* Fetch historical stock market data
* Perform feature engineering
* Train a machine learning regression model
* Predict next-day closing prices
* Visualize actual vs predicted stock prices


# Dataset Source

Stock market data is collected using the `yfinance` Python library from Yahoo Finance.

### Stock Used

* Apple Inc. (`AAPL`)

### Features Used

* Open Price
* High Price
* Low Price
* Volume

### Target Variable

* Next Day Closing Price


# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* yFinance

---

# Machine Learning Model

## Random Forest Regressor

The project uses the Random Forest Regression algorithm because it:

* Handles non-linear relationships effectively
* Reduces overfitting
* Performs well on financial datasets

---

# Project Structure

```bash
project-folder/
│
├── task2_stock_prediction.py
├── task2_stock_prediction.png
└── README.md
```

---

# Features Implemented

## 1. Data Collection

* Downloads real-time stock data from Yahoo Finance

## 2. Feature Engineering

* Creates target variable using next day's closing price

## 3. Time-Series Aware Splitting

* Splits training and testing data without shuffling

## 4. Model Training

* Trains Random Forest Regressor model

## 5. Model Evaluation

Evaluation metrics used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## 6. Data Visualization

* Compares actual vs predicted stock prices

---

# Output

The project generates:

* `task2_stock_prediction.png`

This graph visualizes:

* Actual stock prices
* Predicted stock prices

---

# How to Run

## Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn yfinance
```

## Run the Script

```bash
python task2_stock_prediction.py
```

---

# Sample Results

```text
MAE : $4.43
RMSE: $6.08
```

These results indicate that the model performs reasonably well for short-term stock price prediction.

---

# Key Insights

* Historical stock prices can help estimate future short-term trends.
* Random Forest provides stable predictions for regression tasks.
* Stock prices are highly volatile, so predictions are estimations rather than guaranteed values.

---

# Learning Outcomes

This project demonstrates:

* Financial data analysis
* Feature engineering
* Time-series machine learning
* Regression modeling
* Data visualization using Python

---

# Author

Prepared by:
**Ubaid Ullah**

For:
**DevelopersHub Corporation – AI/ML Engineering Internship**

Developed using Python and machine learning libraries.
