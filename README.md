# ML-Project---Cryptocurrency-Volatility-Prediction
This repository contains all the theory and practical data regarding the Machine Learning Project of Cryptocurrency Volatility Prediction.

# Cryptocurrency Volatility Prediction using Machine Learning

## Project Overview
Cryptocurrency markets are highly volatile. This project aims to **predict cryptocurrency volatility** using historical market data such as **OHLC prices, trading volume, and market capitalization**.  
The model helps traders and financial institutions anticipate high-risk periods and make informed decisions.

This project is built as part of the **Java + DSA | PwSkills Machine Learning Project**.

---

## Problem Statement
The objective is to build a **machine learning model** that predicts **cryptocurrency volatility levels** based on historical data.  
Volatility prediction supports:
- Risk management
- Portfolio allocation
- Trading strategy development

---

## Dataset Description
- Daily historical data for **50+ cryptocurrencies**
- Features include:
  - `date`
  - `symbol`
  - `open`
  - `high`
  - `low`
  - `close`
  - `volume`
  - `market_cap`

Dataset Source:  
Cryptocurrency Historical Prices Dataset (provided in project PDF)

---

## Project Pipeline
1. **Data Collection**
2. **Data Preprocessing**
3. **Exploratory Data Analysis (EDA)**
4. **Feature Engineering**
5. **Model Training**
6. **Model Evaluation**
7. **Hyperparameter Tuning**
8. **Prediction & Deployment (Optional)**

---

## Feature Engineering
The following features were created:
- Daily Returns
- Rolling Volatility (Target Variable)
- Moving Averages (7-day, 14-day)
- Liquidity Ratio (Volume / Market Cap)
- Bollinger Bands
- Average True Range (ATR)

---

## Machine Learning Model
- **Algorithm Used:** Random Forest Regressor
- **Reason:** Handles non-linearity, robust to noise, and works well with financial data

---

## Model Evaluation Metrics
- **RMSE (Root Mean Squared Error)**
- **MAE (Mean Absolute Error)**
- **R² Score**

These metrics were used to evaluate model performance on unseen test data.

---

## Hyperparameter Tuning
- GridSearchCV was used to optimize:
  - Number of trees
  - Maximum depth
  - Minimum samples split

---

## Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TA (Technical Analysis Library)
- Streamlit (for deployment)

---

## Project Structure
crypto-volatility-prediction/
│
├── data/
│ └── crypto_data.csv
│
├── notebooks/
│ └── Crypto_Volatility_Prediction.ipynb
│
├── app.py # Streamlit deployment file
├── model.pkl # Trained ML model
│
├── EDA_Report.pdf
├── HLD.pdf
├── LLD.pdf
├── Pipeline_Architecture.pdf
├── Final_Report.pdf
│
└── README.md


