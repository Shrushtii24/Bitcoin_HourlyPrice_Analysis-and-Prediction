# Bitcoin_HourlyPrice_Analysis-and-Prediction

This project analyzes hourly Bitcoin market data and implements two machine learning models — **Linear Regression** and **LSTM (Long Short-Term Memory)** — for price prediction.

---

## 📊 Dataset

- **Title**: [Bitcoin Market Hourly Trends 2024-2025](https://www.kaggle.com/datasets/gauravkumar2525/bitcoin-market-hourly-trends-2024-2025)
- **Source**: Kaggle
- **Description**: The dataset includes hourly historical data for Bitcoin from 2024 to 2025.  
It contains the following key fields:
  - `Timestamp`
  - `Open`, `High`, `Low`, `Close` Prices
  - `Volume (BTC)`
  - `Volume (Currency)`
  - `Weighted Price`

---

## 🔍 Project Overview

This project includes the following main stages:

1. **Data Loading & Exploration**  
   - Load dataset from Kaggle using `kagglehub`  
   - Perform initial exploration and data checks

2. **Data Preprocessing**  
   - Convert timestamps to datetime format  
   - Handle missing values  
   - Normalize or scale relevant features

3. **Time Series Analysis**  
   - Visualize hourly trends using line plots  
   - Focus on closing price trend over time

4. **Linear Regression Model**  
   - Train a linear regression model using relevant features (e.g., Open, High, Low)  
   - Evaluate using metrics like MAE, RMSE

5. **LSTM Model**  
   - Prepare sequential data (look-back windows)  
   - Build and train LSTM using TensorFlow/Keras  
   - Evaluate predictions

6. **Prediction**  
   - Generate predictions using both models on unseen data  
   - Compare performance visually and statistically

---

## 🧠 Models Used

- **Linear Regression**  
  A traditional machine learning model used for initial baseline performance.

- **LSTM (Long Short-Term Memory)**  
  A deep learning model suited for time series data and long-term dependencies.

---

## 🚀 How to Run This Project

### 1. Prerequisites

Install the following dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn tensorflow kagglehub
