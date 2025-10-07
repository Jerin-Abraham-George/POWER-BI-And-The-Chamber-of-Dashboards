# 🛠️ Project Control Dashboard

## 📌 Overview
The Project Control Dashboard is an interactive Power BI solution designed to monitor and evaluate the performance of a construction project across four key disciplines: Structural, Mechanical, Piping, and Overall Progress. It centralizes critical metrics such as budget hours, earned value, manpower distribution, and schedule adherence to support real-time decision-making and project optimization.

This dashboard enables stakeholders to track progress, assess efficiency, and identify potential delays or resource constraints across multiple workstreams.

![Dashboard Image](https://github.com/Jerin-Abraham-George/Power-BI-Projects/blob/main/Project-Control-Dashboard/Dashboard%20Image.jpg)

---

## 🎯 Objectives
The primary objectives of this dashboard are to:

- Monitor discipline-wise progress and completion forecasts
- Track earned vs. planned vs. actual hours using S-Curve analysis
- Evaluate weekly productivity and manpower trends
- Analyze efficiency metrics including EFF, CPI, and SPI
- Provide visibility into remaining effort and budget utilizatio

---

## 🌟 Key Features

### ✅ Progress Tracking by Discipline
- Overall: 44.2%
- Structural: 68.2%
- Mechanical: 60.5%
- Piping: 25.8%

### 📊 Budget & Earned Value Metric
- Budget Hours: 163,537.7
- Cum. Earned Hours: 72,616
- Cum. Planned Hours: 67,979.2
- Remaining Hours: 88,659.6

### 📈 S-Curve Analysis
- Visual comparison of cumulative planned, earned, and actual hours
- Time-phased performance tracking  

### 👷 Manpower Histogram
- Weekly distribution of workforce
- Identification of peak labor hours 

### 📊 Weekly Productivity Chart
- Green/red bars indicating performance trends
- Highlights underperforming and high-efficiency weeks 

---

## 🧩 Data Model
The dashboard uses a structured dataset containing:

- **Work Metrics**: Budget hours, earned hours, planned hours, remaining work  
- **Progress Data**: Discipline-wise completion percentages  
- **Efficiency KPIs*: CPI, SPI (weekly and cumulative) etc
- **Manpower Data**: Weekly headcount distribution
- **Schedule Data**: Forecasted completion dates per discipline

---

## 🧰 Tools & Technologies

- **Power BI Desktop** – Dashboard development and data modeling  
- **DAX (Data Analysis Expressions)** – Custom measures for performance metrics 
- **Excel/CSV Files** – Used for data import and preprocessing

---

## 🧭 Dashboard Structure

This is a single-page dashboard that includes:
- Discipline-wise progress indicators
- S-Curve for earned vs. planned vs. actual hours
- Weekly productivity and manpower charts
- Efficiency KPIs (EFF, CPI, SPI)
- Forecasted completion dates
- Budget utilization and remaining work metrics

## ✅ Result

This dashboard enabled project managers to:
- Identify that Structural and Mechanical disciplines were ahead of schedule
- Flag Piping as a potential delay risk due to low progress (25.8%)
- Confirm overall project efficiency with CPI > 1.0 and SPI ≈ 1.0, indicating cost-effective execution
- Optimize manpower allocation based on weekly trends
- Forecast realistic completion dates and adjust resource planning accordingly
