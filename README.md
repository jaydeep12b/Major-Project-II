# Smart Prediction System for Stock Market Movements

This project aims to predict future stock price movements using Machine Learning and Deep Learning models.
The system analyzes historical stock market data, identifies key trends, and forecasts future values. 
The prediction engine is integrated with a user-friendly interface to help investors and researchers make informed decisions.

---

## 📌 Features

- Fetch historical stock data using APIs (Yahoo Finance / NSE / CSV)
- Data preprocessing and visualization
- Multiple ML & DL models:
  - CNN Model
  - LSTM (Long Short-Term Memory)
  - CNN-LSTM Hybrid Model
- Model evaluation using RMSE, MSE, and R² Score
- Performance comparison table & graphs
- Streamlit / Flask based web interface 

---

## 🛠️ Technologies Used

| Category       | Tools / Libraries |
|----------------|------------------|
| Language       | Python           |
| Data Handling  | Pandas, NumPy    |
| Visualization  | Matplotlib, Plotly, Seaborn |
| ML/DL Models   | Scikit-learn, TensorFlow / Keras |
| Data Source    | Yahoo Finance (yfinance) |
| Web Interface  | Streamlit / Flask (optional) |

---

## 📂 Project Structure

project-folder/
│── data/
│ └── yahoo finance data
│── models/
│ ├── lstm_model.h5
│── notebooks/
│ └── analysis.ipynb
│── app/
│ └── streamlit_app.py 
│── README.md
└── requirements.txt
