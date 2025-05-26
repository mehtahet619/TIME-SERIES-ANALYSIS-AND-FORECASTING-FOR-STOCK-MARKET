# 📈 Time-Series Analysis and Forecasting for Stock Market

This project uses an LSTM (Long Short-Term Memory) neural network to forecast stock prices based on the past 60 days of historical data. It includes an interactive Gradio interface for real-time predictions.

## 🧠 Project Highlights

- **Model**: Deep learning using LSTM
- **Input**: Past 60 days of stock prices
- **Output**: Predicted future price(s)
- **Interface**: Gradio-based web UI
- **Data Source**: Apple stock market Finance

---

## 📌 Features

- Load and visualize historical stock data
- Preprocess data for time series modeling
- Train/test an LSTM model
- Predict the next day's stock price
- Host the app using Gradio

---
# Research Papers referred-
- Stock Market Prediction Using LSTM Recurrent Neural Network by Adil MOGHARa* ,Mhamed HAMICHEb
https://www.sciencedirect.com/science/article/pii/S1877050920304865 

---

## 📂 Project Structure
├── Apple_Stock_Forecasting.ipynb 
├── utils.py 
├── requirements.txt
├── README.md 
└── saved_models/
└── my_stock_prediction_model.h5 

---

# 🧪 Model Overview

**LSTM Layers:**
-1st LSTM (50 units) + Dropout(0.2)
-2nd LSTM (50 units) + Dropout(0.2)
-Dense Layer (1 unit)

-Loss: Mean Squared Error (MSE)
-Optimizer: Adam
-Epochs: 100 (configurable)

---

# 🧰 Technologies Used

Python
Pandas, NumPy
TensorFlow / Keras
Matplotlib / Plotly
Gradio

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mehtahet619/TIME-SERIES-ANALYSIS-AND-FORECASTING-FOR-STOCK-MARKET.git

cd TIME-SERIES-ANALYSIS-AND-FORECASTING-FOR-STOCK-MARKET

pip install -r requirements.txt

