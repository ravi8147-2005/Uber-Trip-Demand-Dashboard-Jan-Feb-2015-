# 🚕 Uber Trip Demand Analysis –  (Jan–Feb 2015)

This project combines Python and Power BI to analyze Uber trip data from January–February 2015 in New York City. It includes full data processing and visualization workflows: from cleaning and feature engineering in Python to interactive dashboards in Power BI.

---

## 📦 Tools & Technologies

- 🐍 **Python**: Data cleaning, EDA, time-based grouping
- 📊 **Power BI**: KPI cards, charts, calendar heatmap, AI visuals
- 📁 **Pandas**, **Matplotlib**, **Seaborn**

---

## 📁 Project Structure

| File                          | Description                                     |
|-------------------------------|-------------------------------------------------|
| `Uber_Trip.ipynb`             | Python notebook for data analysis & processing  |
| `Uber_Trip_Dashboard.pbx`     | Power BI dashboard built from cleaned data      |
| `Uber-Jan-Feb-FOIL.csv`       | Original Uber trip dataset (raw)                |
| `README.md`                   | Project documentation                           |

---

## ⚙️ Python Workflow Highlights
        
- 📅 Date parsing and formatting
- 🧹 Cleaning missing/duplicate data
- 📈 Visualizing:
  - Daily trip trends
  - Active vehicles
  - Trip-to-vehicle efficiency

---

## 📊 Power BI Dashboard Features

- **Total Trips KPI**
- **Month & Weekday Slicers**
- **Trips by Weekday**
- **Daily Trip Trends**
- **Calendar Heatmap**
- **Trips Per Vehicle Efficiency**
- **Q&A AI Visual** (ask “Which day had most trips?”)

---

## 🧠 AI & Smart Features

- Natural Language Q&A Visual
- Conditional formatting + Smart Narratives (optional)
- ML-ready dataset for future time-series models

---

## 📚 Data Source

- **Uber FOIL API** – NYC, January–February 2015
- Data columns include:
  - `date`, `trips`, `active_vehicles`
  - Derived fields: `weekday`, `week_number`, `month`, `trips_per_vehicle`

---

## 📈 Future Enhancements

- Integrate ML models (ARIMA, LSTM)
- Forecast future trip demand
- Build a Python-to-Power BI pipeline (via CSV export or API)
- Publish live dashboards with Microsoft Fabric

---


---
