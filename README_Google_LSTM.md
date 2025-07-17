
# 📈 Google Stock Price Prediction Using LSTM

This project implements a time series forecasting model using Long Short-Term Memory (LSTM) neural networks to predict Google stock closing prices. It utilizes historical stock data, scales features, and trains an LSTM network on sliding window sequences.

## 📊 Key Features

- Loads and preprocesses Google stock price CSV data
- Applies MinMax scaling to normalize closing prices
- Creates sequences of past 30 days' prices as features
- Trains an LSTM model using Keras
- Evaluates the model using RMSE
- Visualizes real vs predicted stock prices

## 🧰 Tech Stack

- Python
- Pandas, NumPy, scikit-learn
- TensorFlow / Keras
- Matplotlib

## 📁 File Description

- **Notebook**: Contains complete code from preprocessing to model training and evaluation.
- **Google.csv**: Required input CSV with historical Google stock prices.

## 🚀 How to Run

1. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib tensorflow
```

2. Place `Google.csv` in the same directory as the notebook.

3. Open and run the notebook:
```bash
jupyter notebook Google_LSTM_Stock_Prediction.ipynb
```

## 📌 License

This project is for educational use only. Stock data used should comply with public or licensed datasets.
