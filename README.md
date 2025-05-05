# 📈 StockSage – Smart Predictions for Smarter Investments

StockSage is a deep learning-powered web app that predicts stock price trends using historical data and LSTM models. It combines interactive visualization and smart forecasting to support investors and analysts in making informed decisions.

## 🚀 Features

- 📊 Real-time visualization of historical stock prices  
- 🧠 LSTM-based forecasting powered by Keras  
- 🧪 Model training and evaluation in Jupyter Notebook  
- 🌐 Streamlit-powered interactive web UI  

## 🛠️ Tech Stack

- Python 3
- Streamlit
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib

## 📁 Project Structure

| File | Description |
|------|-------------|
| `app.py` | Main Streamlit web app |
| `keras.h5` | Pre-trained LSTM model |
| `MINIPRO.ipynb` | Notebook for training and testing the model |
| `requirements.txt` | Project dependencies |

## ▶️ Run It Locally

```bash
git clone https://github.com/mihika123945/Stock-price-prediction.git
cd Stock-price-prediction
pip install -r requirements.txt
streamlit run app.py
