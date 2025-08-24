# Stock Market Prediction and Forecasting Using Stacked LSTM

## 📌 Project Overview
This project applies **Stacked Long Short-Term Memory (LSTM)** deep learning models to predict stock prices.  
Using Apple (AAPL) historical stock data, the model learns sequential price patterns and forecasts future values.

---

## 📊 Key Objectives
- Perform **time series forecasting** on stock market data.  
- Apply **data scaling and preprocessing** for LSTM models.  
- Train a **stacked LSTM neural network** for better sequence learning.  
- Evaluate model performance with RMSE on train and test sets.  

---

## 🗂️ Dataset
- **Source**: Apple Stock Price Dataset (`AAPL.csv`)  
- **Features used**: Closing prices  

---

## 🔍 Methodology
1. Data preprocessing with **MinMaxScaler**  
2. Train-test split (65%-35%)  
3. Sequence generation for time series input  
4. Model building with **Stacked LSTM layers** in Keras/TensorFlow  
5. Prediction and visualization  

---

## 📈 Results
- **Train RMSE**: 42.72  
- **Test RMSE**: 93.46  
- Model successfully captures stock price trends, though accuracy decreases on unseen data.  

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib  
- **Scikit-learn** for preprocessing  
- **TensorFlow/Keras** for LSTM modeling  
- **Jupyter Notebook** for implementation  

