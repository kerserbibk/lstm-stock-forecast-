# 📈 LSTM-Based Stock Price Direction Prediction

This project uses a Long Short-Term Memory (LSTM) neural network implemented in PyTorch to predict whether the stock price will **go up**, **go down**, or **stay the same** on the next day based on the recent trend.

## 🧠 Model Overview

- Framework: **PyTorch**
- Model: **LSTM** with 2 layers+Multi Head Attention Layer
- Task: **Classification and adapting trends** (Up = 1, Down = 0)
- Loss: **MSELoss**
- Output: Class label for next day's price direction

## 🔢 Dataset

- **Source:** World Stock Prices Dataset from Kaggle till 5May
- **Feature used:** Closing prices
- **Preprocessing:** MinMaxScaler for normalization
- **Sequence length:** 30-45 previous days used to predict the next

## 📊 Features

- Predicts the **direction** of the stock price (not exact value)
- Visualizes the **true vs predicted** class labels
- Prints a **final prediction** for the next day's price movement

## 🚀 How to Run

1. Upload the dataset (`stocks.csv`) to Google Colab
2. Run the notebook cell by cell
3. At the end, see the predicted movement and comparison chart

### Example Output:

