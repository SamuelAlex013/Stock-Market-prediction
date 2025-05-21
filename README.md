# 🧠 Stock Price Prediction with Deep Learning

A comparative analysis of deep learning models — LSTM, BiLSTM, and GRU — for stock market forecasting using historical stock data.

## 📌 Project Summary

This project explores the performance of three advanced recurrent neural network architectures for stock price prediction:

- **LSTM (Long Short-Term Memory)**
- **BiLSTM (Bidirectional LSTM)**
- **GRU (Gated Recurrent Unit)**

Using a time-series dataset of Bajaj stock prices from 2003 to 2020, we evaluated and compared each model’s accuracy using standard metrics such as **MSE**, **MAPE**, and **RMSE**.

## 🚀 Features

- 📈 Forecasts stock prices using deep learning
- 🧪 Preprocessing: Cleaning, Normalization, Interpolation
- 🔍 Models: LSTM, BiLSTM, GRU (built with TensorFlow/Keras)
- 📊 Visualization: Training loss and actual vs predicted values
- 📁 Dataset: Historical stock data from Kaggle

## 🗃 Dataset

- Stock: Bajaj
- Records: 4388
- Features: Open, Close, High, Low, Volume, etc.
- Date Range: 2003–2020

## 📊 Evaluation Metrics

| Model   | MSE        | MAPE       | RMSE       |
|---------|------------|------------|------------|
| LSTM    | 7.20e-05   | 2.61e-02   | 8.50e-03   |
| BiLSTM  | 8.50e-05   | 3.05e-02   | 9.23e-03   |
| **GRU** | **4.20e-05** | **1.86e-02** | **6.47e-03** |

🔍 **GRU outperformed** the others in all three metrics due to its lightweight architecture and fast convergence.

## 📉 Visualizations

- Training vs Validation Loss graphs for each model
- Actual vs Predicted price plots
- Comparative prediction plot for all models

## 🛠 Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn

## 🔍 Key Takeaways

- GRU offered the best trade-off between accuracy and training time.
- BiLSTM did not show significant improvement for stock data due to lack of future information in real-time forecasting.
- Proper preprocessing and architecture tuning play a critical role in performance.

## 🔮 Future Work

- Integrate Transformer models like BERT or GPT
- Incorporate sentiment analysis and external market indicators
- Explore hybrid & ensemble models
- Build a real-time prediction system



