#  Stock Price Prediction using LSTM

# Project Overview
This project demonstrates how to predict stock prices using a **Long Short-Term Memory (LSTM)** neural network. 
We fetch historical stock data from **Yahoo Finance**, preprocess it, and train a deep learning model to forecast future prices.

The project is **generic** → you can input any stock ticker (e.g., `AAPL`, `MSFT`, `TSLA`) and visualize predictions.

---

# Features
- Fetch stock data from **Yahoo Finance (yfinance)**
- Perform **Exploratory Data Analysis (EDA)** with visualizations
- Data preprocessing & scaling with **MinMaxScaler**
- Build & train an **LSTM model** using TensorFlow/Keras
- Predict and visualize stock prices vs. actual prices
- Forecast future stock movement

---

# Project Structure
```
📦 stock-prediction-lstm
 ┣ 📜 stock_prediction.ipynb   # Jupyter notebook with code
 ┣ 📜 README.md                 # Project documentation
 ┣ 📜 requirements.txt          # Dependencies
 ┗ 📜 .gitignore                # Git ignore file
```

---

# Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/stock-prediction-lstm.git
cd stock-prediction-lstm
pip install -r requirements.txt
```

---

# Usage
Run the Jupyter Notebook:
```bash
jupyter notebook stock_prediction.ipynb
```
Inside the notebook, change the ticker (e.g., `"AAPL"`, `"MSFT"`, `"TSLA"`) to fetch different stock data.

---

# Example Output
- Stock price history with moving averages  
- Predicted vs. Actual stock prices  
- Future price forecast  

---

# Requirements
See `requirements_stock.txt` for full list.

---

