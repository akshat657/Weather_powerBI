# Weather_powerBI
# 🌦 Power BI Real-Time Weather Dashboard



## 📌 Overview
This project is a **real-time weather dashboard** built in **Power BI**, powered by live data from the [WeatherAPI.com](https://www.weatherapi.com) service.

Instead of static CSV files, this dashboard connects directly to **live JSON API data**, bringing **current weather, forecasts, and air quality metrics** into an interactive and visually appealing interface. It is designed with a **dark theme**, dynamic filters, and automatic refresh capability.

---

## ✨ Features
- 🌐 **Live Data**: Fetches real-time weather information from multiple cities.
- 🧹 **Data Modeling**: Separate tables for current weather, forecasts, and air quality.
- 🎨 **Dark-Themed Design**: Sleek and easy-to-read visuals.
- 🚦 **Dynamic KPIs**: Color-coded alerts for extreme weather and high pollution.
- 🌅 **Extra Insights**: Sunrise/sunset, precipitation probability, temperature trends.
- 🔄 **Automatic Refresh**: Always up-to-date when published to Power BI Service.

---

## 📂 Folder Structure

PowerBI-Weather-Dashboard/
│
├── Dashboard.pbix # Main Power BI dashboard file
├── API_Steps.md # How to get API key and test endpoints
├── Images/
│ ├── dashboard_preview.png
│ └── dark_theme_example.png
├── weather_icons/ # Optional icons used in dashboard
└── README.md # This file

---

## ⚙️ Setup Instructions

### 1️⃣ Get Your API Key
1. Go to [weatherapi.com](https://www.weatherapi.com)
2. Sign up for a free account (you can use a temp email for demo purposes).
3. Copy your **API Key**.

### 2️⃣ Check API Endpoints
Example endpoints:
```bash
# Current weather for London
http://api.weatherapi.com/v1/current.json?key=YOUR_KEY&q=London

# 7-day forecast for New York
http://api.weatherapi.com/v1/forecast.json?key=YOUR_KEY&q=New York&days=7

3️⃣ Connect to Power BI
Open Power BI Desktop.

Go to Get Data → Web.

Paste the API URL and replace CITY & YOUR_KEY as needed.

Load and transform data in Power Query.

4️⃣ Data Transformation
Merge multiple city data into one table.

Split into Current, Forecast, and Air Quality tables.

Remove duplicates, format date/time columns.

Create relationships between tables.

5️⃣ Dashboard Design
Apply dark theme.

Add slicers for city and date.

Insert KPIs with conditional formatting.

Display weather icons dynamically from URL.

6️⃣ Automatic Refresh
Publish to Power BI Service.

Go to Datasets → Schedule Refresh and set desired interval.

🔮 Future Enhancements
🌍 Support for global maps with live weather overlay.

📊 Additional metrics like historical trends.

📱 Mobile-friendly Power BI dashboard view.

📜 License
This project is licensed under the MIT License.

🤝 Connect with Me
💼 LinkedIn
www.linkedin.com/in/akshat-khandelwal-79647a245
