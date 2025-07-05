
# 🌨️ US Weather Data Analysis

This project analyzes weather event data across the United States to identify trends in severe and light weather conditions, their frequency, locations, and impact.

---

## 📁 **Dataset Overview**

The dataset contains weather event records with the following columns:

- `EventId` : Unique identifier for each weather event.
- `Type` : Type of weather event (e.g., Snow, Fog).
- `Severity` : Severity level (e.g., Light, Severe).
- `StartTime(UTC)` & `EndTime(UTC)` : Start and end time in UTC.
- `Precipitation(in)` : Precipitation amount in inches.
- `TimeZone` : Time zone of the event.
- `AirportCode` : Nearest airport code for reference.
- `LocationLat` & `LocationLng` : Latitude and longitude coordinates.
- `City`, `County`, `State`, `ZipCode` : Location details.

Example:  
Most events shown are `Snow` or `Fog` in `Saguache, Colorado` (CO) near airport `K04V`.

---

## 📊 **Notebook**

- **File:** `US_Weather_data_analysis.ipynb`
- **Content:**  
  - Data cleaning and preprocessing
  - Date-time parsing and event duration calculations
  - Analysis of event types and severity levels
  - Visualizations of weather event frequency and geographic distribution

---

## ✅ **Key Insights**

- Identify which weather types are most frequent in specific regions.
- Compare light vs. severe event counts.
- Analyze the duration of weather events.
- Explore patterns in precipitation levels and seasonal occurrence.

---


## 📈 **Tools Used**

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib & Seaborn for charts
- Datetime operations for time analysis

---

## 🚀 **Next Steps**

- Add weather type mapping to seasons.
- Create geospatial visualizations using Folium or Plotly.
- Connect with external weather APIs for live comparison.
- Build predictive models for severe weather forecasting.

---

## 📃 **Author**

**Project by:** *Shrey Koradiya*  
