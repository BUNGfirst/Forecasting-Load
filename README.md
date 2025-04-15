# Forecasting-Load
## ⚡ Electricity Load Forecasting using Deep Learning & Power BI

This project aims to predict electricity demand based on weather and temporal features using deep learning (TensorFlow).  
The results are visualized through an interactive Power BI dashboard to support real-time monitoring and decision-making.

---

## 📌 Project Highlights

- **Task**: Time Series Regression – Forecast national electricity demand
- **Model**: Deep Neural Network (DNN) using TensorFlow (Keras API)
- **Data Preprocessing**: Scaling, time feature extraction (year, month, hour), train-validation-test split
- **Visualization**: Interactive dashboard created using **Power BI**
- **Evaluation Metrics**: MAE, MAPE, Absolute Error trends

---

## 📊 Dataset

The dataset used in this project is sourced from Kaggle:  
🔗 [Electricity Load Forecasting Dataset](https://www.kaggle.com/datasets/saurabhshahane/electricity-load-forecasting/data)

It includes:
- Hourly national demand (`nat_demand`)
- Weather indicators: temperature, humidity, wind speed, etc.
- Time columns (timestamp, day, holiday info)

---

## 🚀 Tools and Technologies

| Tool | Purpose |
|------|---------|
| `Python` | Data processing, model training |
| `TensorFlow / Keras` | Deep learning model |
| `scikit-learn` | Scaling & evaluation metrics |
| `Power BI` | Dashboard visualization |
| `Pandas / NumPy` | Data handling and transformation |

---

## 🧠 Key Features in Power BI

- Time-series comparison of **Actual vs Predicted** demand
- Error analysis using **Abs Error** and **APE (Absolute Percentage Error)**
- Filterable views (e.g., high-error periods)
- KPI cards summarizing model performance

---
![Model Performance](images/Performance.jfif)