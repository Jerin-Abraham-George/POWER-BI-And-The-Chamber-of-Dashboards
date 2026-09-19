# 🌦️ Weather Forecasting Dashboard

## 📘 Overview

The **Weather Forecasting Dashboard** is an interactive **Power BI** solution designed to provide a clear and visually engaging overview of current weather conditions, upcoming temperature trends, air quality, precipitation probability, and other important atmospheric indicators.

The dashboard focuses on **Lucknow** and combines multiple weather parameters into a single-page interface, allowing users to quickly understand current conditions and forecast patterns.

> 📌 **Note:** The dashboard screenshot represents the weather data available at the time of the displayed update (**23 July**). Values shown in the dashboard should be treated as a snapshot of the underlying weather dataset.

---

## 🎯 Objectives

- To provide a consolidated overview of current weather conditions.
- To visualize **temperature forecasts** across upcoming days.
- To monitor important atmospheric indicators such as humidity, wind speed, visibility, pressure, and UV index.
- To analyze **Air Quality Index (AQI)** and individual pollutant levels.
- To visualize the probability of rainfall over the forecast period.
- To present complex weather information through an intuitive and visually appealing Power BI interface.
- To enable quick interpretation of weather conditions through interactive visualizations and KPI cards.

---

## 🔑 Key Features

### 🌡️ Current Weather Overview

The dashboard provides a prominent summary of the current weather conditions for **Lucknow**, including:

- Current temperature
- Weather condition
- Humidity
- Wind speed
- Visibility
- Atmospheric pressure
- UV index
- Precipitation

The large temperature card provides an immediate understanding of the current weather, while supporting KPI cards provide additional environmental context.

---

### 📈 Temperature Forecast

The **Weather Forecast** section displays the expected temperature trend across the upcoming days.

The visualization includes:

- Daily forecast temperatures
- Line chart showing temperature movement
- Day-by-day comparison
- Visual identification of warming and cooling trends

The displayed forecast covers **Wednesday through Tuesday**, making it easy to identify temperature changes throughout the forecast period.

---

### 🌅 Sunrise & Sunset

A dedicated **Sunrise & Sunset** section provides:

- Sunrise time
- Sunset time
- Visual representation of the daily solar cycle

This provides additional context for understanding daylight availability throughout the day.

---

### 💧 Environmental Metrics

The dashboard tracks several important environmental indicators through dedicated KPI cards:

| Metric | Value |
|---|---:|
| 🌡️ Temperature | 35°C |
| 💧 Humidity | 60 |
| 💨 Wind Speed | 12.2 kph |
| 👁️ Visibility | 5 km |
| 🌡️ Pressure | 29.38 |
| ☀️ UV Index | 1.90 |
| 🌧️ Precipitation | 0 |

These metrics provide a quick snapshot of the atmospheric conditions at the selected location.

---

### 🌫️ Air Quality Analysis

The **Air Quality Index** section provides a detailed breakdown of overall air quality along with individual pollutant concentrations.

The dashboard displays:

- **PM10**
- **PM2.5**
- **SO₂**
- **NO₂**
- **O₃**
- **CO**

The central AQI visualization provides an immediate indication of overall air quality, while the surrounding pollutant indicators allow users to examine individual pollutant levels.

The displayed snapshot contains:

- **AQI:** 105
- **PM10:** 105
- **PM2.5:** 84.18
- **SO₂:** 15
- **NO₂:** 8.51
- **O₃:** 137
- **CO:** 471.75

The dashboard categorizes the displayed AQI as **Moderate**.

---

### 🌧️ Chance of Rain

The **Chance of Rain** visualization provides a day-by-day comparison of precipitation probability.

The horizontal bar chart makes it easy to identify:

- Days with higher precipitation probability
- Days with relatively lower rainfall probability
- Changes in rainfall likelihood throughout the forecast period

This complements the temperature forecast by providing another perspective on upcoming weather conditions.

---

## 📊 Dashboard Layout

The dashboard follows a **single-page design** divided into several functional sections.

### 📍 Location & Current Conditions

The upper-left section provides the selected location and current weather information.

- **Location:** Lucknow
- **Current Condition:** Mist
- **Current Temperature:** 35°C

---

### 📈 Forecast Analysis

The central upper section contains the temperature forecast line chart.

It provides a visual representation of how temperatures are expected to change throughout the forecast period.

---

### 🌅 Solar Information

The upper-right section displays sunrise and sunset information, providing additional context around daylight hours.

---

### 💨 Weather KPI Section

The lower-left section contains individual cards for:

1. Humidity
2. Wind Speed
3. Visibility
4. Pressure
5. UV Index
6. Precipitation

This arrangement allows users to quickly scan the most important weather indicators.

---

### 🌫️ Air Quality Section

The central lower section focuses on air quality.

It combines:

- Circular AQI visualization
- AQI classification
- Pollutant values
- Color-coded pollutant indicators

This creates a dedicated analytical area for understanding atmospheric pollution.

---

### 🌧️ Rainfall Probability

The lower-right section contains the **Chance of Rain** visualization, allowing users to compare precipitation probabilities across the forecast period.

---

## 🧰 Tools & Technologies

- **Microsoft Power BI** – Dashboard development and interactive visualization
- **Power Query** – Data transformation and preparation
- **DAX (Data Analysis Expressions)** – Calculated measures and analytical metrics
- **Data Visualization** – KPI cards, line charts, bar charts, and custom dashboard layouts

---

## 🎨 Design & User Experience

The dashboard uses a modern **dark-themed interface** with contrasting colors to make important information immediately visible.

### Key Design Elements

- 🟠 **Orange:** Temperature and weather trend visualization
- 🟡 **Yellow:** AQI and selected environmental indicators
- 🟢 **Green:** Lower-level pollutant indicators
- 🟣 **Purple:** CO indicator
- 🌑 **Dark Background:** Provides strong contrast and reduces visual clutter
- 📊 **KPI Cards:** Enable rapid interpretation of weather conditions
- 📈 **Charts:** Provide trend-based analysis rather than relying only on individual numbers

The large temperature card acts as the primary visual anchor, while the surrounding cards and charts provide progressively more detailed information.

---

## 🗂️ Dashboard Structure

This is a **single-page Power BI weather analytics dashboard** containing the following major sections:

### 🌡️ Weather Summary

1. Current temperature
2. Current weather condition
3. Humidity
4. Wind speed
5. Visibility
6. Atmospheric pressure
7. UV index
8. Precipitation

### 📈 Forecast View

1. Multi-day temperature forecast
2. Temperature trend analysis
3. Daily temperature comparison
4. Identification of warming and cooling patterns

### 🌅 Solar Information

1. Sunrise time
2. Sunset time
3. Daylight-related information

### 🌫️ Air Quality View

1. Overall AQI
2. AQI classification
3. PM10
4. PM2.5
5. SO₂
6. NO₂
7. O₃
8. CO

### 🌧️ Precipitation View

1. Daily chance of rain
2. Forecast-period comparison
3. Identification of relatively higher and lower precipitation probabilities

---

## 🔍 Key Insights from the Dashboard

Based on the values visible in the provided dashboard:

- 🌡️ **35°C** is displayed as the current temperature for Lucknow.
- 💧 **Humidity is 60**.
- 💨 **Wind speed is 12.2 kph**.
- 👁️ **Visibility is shown as 5 km**.
- ☀️ The displayed **UV Index is 1.90**.
- 🌧️ **Precipitation is currently shown as 0**.
- 📈 The forecast shows temperatures remaining around the **low-to-mid 30°C range** for most of the displayed period.
- 📉 A noticeable temperature decrease is visible toward Monday.
- 🌫️ The displayed **AQI is 105**, categorized by the dashboard as **Moderate**.
- 🏭 The dashboard provides pollutant-level detail rather than relying solely on the overall AQI.
- 🌧️ The rainfall chart shows variation in precipitation probability across the forecast days.

---

## 🚀 Project Highlights

This project demonstrates how **Power BI can transform multiple weather-related metrics into a unified analytical dashboard**.

Key highlights include:

- 📊 **Comprehensive Weather Monitoring** – Multiple weather parameters are presented in one view.
- 🌡️ **Forecast Trend Analysis** – Temperature changes are represented visually across multiple days.
- 🌫️ **Air Quality Monitoring** – AQI and individual pollutants are analyzed together.
- 🌧️ **Precipitation Analysis** – Rain probability is presented using an easy-to-interpret comparative chart.
- 🎨 **Modern Dashboard Design** – A dark UI combined with bright accent colors improves visual hierarchy.
- ⚡ **Quick Information Access** – Important weather information can be understood at a glance.
- 📱 **Structured Information Architecture** – Current conditions, forecasts, environmental metrics, and air quality are separated into clear visual sections.

---

🔴🟢 *“"Turning weather data into clear, actionable visual insights — one forecast at a time.”*

