# Real-Time-Weather-Dashboard

---

## 🌤️ Real-Time Weather Data Dashboard

This project is a complete hands-on **data pipeline and dashboard** that demonstrates end-to-end data handling and visualization of real-time weather conditions across multiple cities. It covers key weather parameters such as temperature, humidity, pressure, wind speed, and weather descriptions.

---

### 📌 Project Overview

- **Goal:** Build a comprehensive weather dashboard using real-time data components.
- **Tools Used:**
  - 🐍 Python (for data preprocessing)
  - 📊 Tableau Public (for visualization)
  - 🧹 Pandas (for cleaning and merging datasets)
- **Data Type:** Time-series weather data across 37 cities
- **Output:** A dynamic dashboard to explore weather trends over time.

---

### 📁 Dataset Details

The following CSVs were combined into a single dataset:

| Dataset | Description |
|--------|-------------|
| `temperature.csv` | Daily temperature readings |
| `humidity.csv` | Daily humidity levels |
| `pressure.csv` | Atmospheric pressure |
| `wind_speed.csv` | Wind speed in km/h |
| `wind_direction.csv` | Wind direction by compass |
| `weather_description.csv` | General weather condition |
| `city_attributes.csv` | Metadata including location coordinates |

---

### 🔧 Process Workflow

1. **Data Preprocessing**
   - Merged multiple datasets by `datetime` and `city`
   - Converted wide format to long format
   - Cleaned missing values and standardized column names

2. **Final Output**
   - Exported as `final_weather_data.csv`
   - Imported to Tableau Public

3. **Dashboard Features**
   - 📈 Time-series line charts for key metrics
   - 🗺️ Interactive city filters
   - 🧭 Weather condition highlights
   - 🎨 Themed with a clean, user-friendly layout

---

### 📸 Dashboard Preview

> Add a screenshot or Tableau Public link here:

📍 **Live Dashboard:** [View on Tableau Public] https://public.tableau.com/app/profile/shahwar.s3182/viz/Real-TimeWeatherDashboard/Dashboard1

---

### 💡 What I Learned

- Handling multi-source real-time weather data
- Creating time-series visualizations and filters
- Designing a layout for effective storytelling in dashboards
- Tableau best practices (color, filters, tooltips, interactivity)

---

### 🚀 Skills Demonstrated

- Data Wrangling (Pandas, CSVs)
- Exploratory Data Analysis (EDA)
- Dashboard Design (Tableau)
- End-to-End Pipeline Development

---

