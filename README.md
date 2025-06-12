# Time Series Forecasting Project – Demand Forecasting

## 📊 Objective
The goal of this project is to perform time series forecasting on demand data using statistical and smoothing models. I used Power Query for ETL, and Excel for modeling, visualization, and evaluation.

---

## 📁 Dataset
- **Source**: Downloaded from [Kaggle](#) *(insert link if public)*
- Contains daily/monthly demand data with timestamps
- Handled missing values and outliers

---

## 🔧 Tools Used
- Excel (Power Query, Pivot, Power Pivot)
- Excel Data Model
- Time Series Functions
- Charts & Forecasting Models

---

## 🧹 Data Cleaning & Preparation
- Loaded data into Power Query for preprocessing
- Filled missing values using linear interpolation
- Removed outliers using standard deviation method
- Created Date/Time column for granularity

---

## 📈 Statistical Analysis
- Checked **seasonality** and **trend** using decomposition
- Performed **Dickey-Fuller Test** for stationarity
- Identified presence of **random walk** in data

---

## 📉 Forecasting Models Used
1. **Moving Average**
   - Applied 3-point and 5-point MA for short-term trend smoothing
2. **Holt-Winters Method**
   - Triple exponential smoothing with trend and seasonality
3. **Tracker Sheet**
   - Tracked errors in actual vs forecast (MAPE, RMSE)
   - Highlighted seasonal anomalies and model deviations

---

## 📊 Results
| Model           | MAPE (%) | RMSE |
|----------------|----------|------|
| Moving Average | XX.X     | XXX  |
| Holt-Winters   | XX.X     | XXX  |

**Holt-Winters outperformed Moving Average in capturing seasonal effects.**

---

## 📂 Folder Structure
