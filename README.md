# GeoPulse Chicago 🚴📍

End-to-end geospatial analytics and machine learning project using Chicago Divvy mobility data for demand forecasting, spatial insights, and dashboard reporting.

---

## 🔥 Overview
GeoPulse Chicago transforms raw bike-share trip data into business-ready insights using data engineering, geospatial analysis, visualization, and predictive modeling.

This project demonstrates how real-world mobility data can be used to understand rider behavior, identify high-demand zones, and forecast future trip demand.

---

## 🚀 Key Features
- Processed **137K+ real trip records**
- Cleaned and transformed raw data using Python + Pandas
- Built geospatial maps and heatmaps using GeoPandas + Folium
- Performed spatial joins with Chicago neighborhood boundaries
- Created dashboard-style KPI and trend visualizations
- Built a Random Forest model for hourly demand prediction
- Evaluated model performance with feature importance and diagnostics

---

## 🛠 Tech Stack
- Python
- Pandas
- GeoPandas
- Shapely
- Scikit-learn
- Matplotlib
- Folium
- Jupyter Notebook
- Git / GitHub

---

## 📊 Business Questions Solved
- What hours have the highest trip demand?
- How do members vs casual riders behave differently?
- Which neighborhoods generate the most rides?
- How can future hourly demand be forecasted?
- What factors most influence rider demand?

---

## 📁 Repository Structure

geopulse-chicago/
│── notebooks/
│   └── GeoPulse_Working.ipynb
│── data/
│   └── processed/
│── images/
│── README.md
│── requirements.txt

---

## 📈 Key Insights
- Peak ride demand occurs during commute hours
- Member riders show stronger recurring weekday behavior
- Casual riders tend to take longer rides
- Time of day is the strongest predictor of demand
- High-volume neighborhoods help guide resource planning

---

## 🤖 Machine Learning Model

**Model Used:** Random Forest Regressor

**Target Variable:**  
- Hourly Trip Count

**Features Used:**  
- Start Hour  
- Day of Week  
- Month  
- Day of Month

**Evaluation:**  
- Actual vs Predicted Analysis  
- Feature Importance Ranking

---

## 💼 Skills Demonstrated
- Data Engineering
- Geospatial Analytics
- Machine Learning
- Dashboarding
- Business Intelligence
- Exploratory Data Analysis
- Predictive Modeling

---

## 🔮 Future Enhancements
- Add weather data for stronger forecasting
- Deploy interactive dashboard
- Integrate PostgreSQL/PostGIS
- Build real-time streaming pipeline
- Add route optimization recommendations

---

## 👤 Author
Abhinav Kiran
