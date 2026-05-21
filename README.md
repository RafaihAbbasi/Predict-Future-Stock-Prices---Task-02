# Short-Term Stock Price Prediction

## Project Overview
This project was developed as part of the DevelopersHub AI/ML Engineering Internship Task 2.

The goal of this project is to predict the next day's stock closing price using historical stock market data obtained from Yahoo Finance.

---

## Objective

To build a machine learning model capable of predicting future stock prices using previous market information such as Open, High, Low, Volume, and technical indicators.

---

## Dataset Used

Source: Yahoo Finance API (yfinance library)

Stock Used: Apple Inc. (AAPL)

Date Range:
- Start Date: 2021-01-01
- End Date: 2026-01-01

Features Used:
- Open Price
- High Price
- Low Price
- Volume
- Moving Average (5 days)
- Moving Average (10 days)

Target Variable:
- Next Day Closing Price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- yfinance

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed missing values
- Created Moving Average features:
    - MA_5
    - MA_10
- Created target column using shifted closing prices
- Performed train-test split while preserving chronological order

---

## Model Applied

Machine Learning Model:

Random Forest Regressor

Reason for selection:
Random Forest captures complex patterns and non-linear relationships better than basic linear models.

---

## Evaluation Metrics

The following metrics were used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Visualizations

The project includes:

- Historical stock closing trend
- Correlation heatmap
- Distribution plot
- Actual vs Predicted stock prices
- Feature importance graph

---

## Results and Findings

- The model successfully predicted short-term stock price trends.
- Moving average features improved prediction performance.
- Random Forest performed effectively for stock prediction.
- Feature importance analysis identified influential variables affecting predictions.

---

## Future Improvements

Potential enhancements:

- Implement LSTM neural networks
- Add more technical indicators
- Use larger datasets
- Predict multiple future days

---

## Project Structure

├── Task2_StockPrediction.ipynb

├── README.md

└── requirements.txt

---

## Author

Abdul Rafaih Mujeeb Abbasi

AI/ML Engineering Internship – DevelopersHub Corporation
