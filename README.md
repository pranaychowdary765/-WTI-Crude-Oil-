### 🛢️ 2️⃣ WTI Crude Oil — Price & Direction Forecasting
```markdown
# 🛢️ WTI Crude Oil — Price & Direction Forecasting

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![BiLSTM](https://img.shields.io/badge/Model-LSTM%2FBiLSTM-orange?style=for-the-badge)
![Commodities](https://img.shields.io/badge/Domain-Commodities-yellow?style=for-the-badge)

## 📘 Overview
Forecasts **next-day WTI Crude Oil prices and direction (up/down)** using LSTM & BiLSTM models.  
Focuses on handling **volatility and macro-event sensitivity** in energy markets.

---

## 📊 Dataset
**Attributes:** Date, Open, High, Low, Close, Volume  
**Goal:** Predict next-day Close and direction  
📁 *Path:* `Datasets/Main 2.csv`

---

## 🧠 Model
LSTM(128) → Dropout(0.3) → LSTM(64) → Dense(1)
BiLSTM for directional classification

yaml
Copy code
**Metrics:** RMSE, MAE, Accuracy, F1  
**Baselines:** Naive, ARIMA  

---

## 🚀 Run the Project
```bash
git clone https://github.com/pranaychowdary765/-WTI-Crude-Oil-.git
cd WTI-Crude-Oil
pip install -r requirements.txt
python main.py
📈 Result Summary
Stable forecasts with good trend capture; minor lag during high-volatility shocks.
📈 Result Summary
