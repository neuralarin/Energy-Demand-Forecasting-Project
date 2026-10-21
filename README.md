# Electricity Demand & Solar Generation Forecasting ⚡

## 🙂 Overview
This project focuses on forecasting electricity demand and solar power generation using historical data and ARIMA models. This project was built to understand time series analysis and forecasting techniques.

---

## 💡 Problem Statement & Business Impact
- Fluctuating electricity demand and solar power generation make energy planning challenging.
- **Goal:** Built an ARIMA-based forecasting system to predict electricity demand and solar power generation.
- **Business value:** Supports efficient resource allocation, reduces operational costs, and improves energy management and grid planning.

---

## 📊 Dataset Overview

The dataset contains historical electricity consumption and solar generation data collected over time.
**Features:** `IT_load_new`, `IT_solar_generation`, `utc_timestamp`

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Statsmodels (ARIMA)
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```
├── data
│   └── data.csv
├── images
├── notebooks
│   └── Notebook.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

---

## 🔄 Workflow

### 1. Data Analysis

* Loaded and explored the dataset.
* Checked data quality and feature distributions.
* Visualized historical trends.

### 2. Data Preprocessing

* Selected relevant time series.
* Prepared data for forecasting.
* Split data into training and testing sets.

### 3. Model Training

* Built ARIMA models for forecasting.
* Generated predictions for test data.
* Compared actual vs predicted values.

### 4. Model Evaluation

* Evaluated forecasting performance using RMSE.
* Visualized prediction results.

---

## 📈 Data Visualization

### 1. Load And Solar Generation Over Time 
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/1.load_and_solar_generation_over_time.png" width="100%">

### 2. Solar Generation Over Time 
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/2.solar_generation_over_time.png" width="100%">

### 3. ACF (Autocorrelation Function) plot and PACF (Partial Autocorrelation Function) plot
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/3.acf_and_pacf_plots.png" width="100%">

### 4. Actual vs Predicted Load Values
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/4.actual_vs_predicted_load_values.png" width="100%">

### 5. ACF (Autocorrelation Function) plot and PACF (Partial Autocorrelation Function) plot
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/5.acf_and_pacf_plots.png" width="100%">

### 6. Actual vs Predicted Load Values
<img src="https://github.com/neuralarin/Energy-Demand-Forecasting-Project/blob/main/images/6.actual_vs_predicted_load_values.png" width="100%">

---

## 🚀 Future Scope

* Deploy the model using Streamlit.
* Experiment with advanced forecasting models such as SARIMA, Prophet, and LSTM.
* Automate hyperparameter tuning.
* Forecast future demand for longer time horizons.
* Integrate real-time data for live forecasting.
