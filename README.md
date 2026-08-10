# 🚍 Transportation Performance Dashboard

### Excel Business Intelligence & Operational Performance Analytics

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-Automation-blue)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-purple)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-orange)

---

## 📊 Project Overview

The **Transportation Performance Dashboard** is an interactive Microsoft Excel Business Intelligence solution developed to transform transportation operational data into an executive-level performance monitoring and reporting tool.

The project analyses transportation operations across **2024 and 2025**, providing management with a centralized view of revenue, costs, profitability, passenger activity, trip volumes, vehicle utilization, route performance, branch performance, driver performance and service reliability.

The dashboard combines **PivotTables, interactive slicers, Excel formulas, KPI calculations, data visualizations and VBA automation** to create a dynamic reporting environment.

---

## 🎯 Project Objective

The objective of this project was to transform operational transportation data into an interactive decision-support dashboard that enables management to:

- Monitor key transportation performance indicators
- Analyse revenue and profitability
- Track fuel and operating costs
- Monitor passenger and trip volumes
- Evaluate vehicle occupancy
- Compare route and branch performance
- Monitor driver performance
- Analyse On-Time performance
- Compare current-month performance against the previous month
- Quickly identify favourable and unfavourable performance movements

---

## 🖥️ Dashboard Preview

> Dashboard screenshot will be added here.

![Transportation Performance Dashboard] <img width="1555" height="1600" alt="Dashboard Full View" src="https://github.com/user-attachments/assets/624f0d5c-c899-468d-9163-d2e715924d35" />


---

## 📌 Key Performance Indicators

### Financial KPIs

- Total Revenue
- Total Fuel Cost
- Total Operating Cost
- Net Profit
- Profit Margin
- Revenue per Trip

### Operational KPIs

- Total Trips
- Total Passengers
- Vehicle Occupancy
- On-Time Rate

### Performance Rankings

- Best Route
- Best Branch
- Best Driver

---

## 🎛️ Interactive Dashboard

The dashboard provides interactive filtering through slicers for:

- Year
- Month
- Branch
- Route
- Vehicle Type
- Driver

The slicers are connected to relevant PivotTables, allowing applicable KPI cards and visualizations to update dynamically.

This enables users to move from an overall business view into more detailed operational analysis without manually modifying calculations.

---

## 📈 Dashboard Analysis

The dashboard provides several analytical perspectives.

### Revenue Performance

Revenue can be analysed across:

- Monthly periods
- Branches
- Routes

### Operational Performance

The dashboard monitors:

- Trip volumes
- Passenger volumes
- Vehicle occupancy
- Service reliability

### Performance Analysis

Management can identify high-performing:

- Routes
- Branches
- Drivers

---

## 📅 Month-over-Month Performance Analysis

A key feature of the dashboard is the **Month-over-Month (MoM) performance engine**.

The dashboard automatically compares selected-month performance against the previous month.

Example:

> 🟢 **▲ +22.6% vs Last Month**

The MoM indicators dynamically respond to the dashboard's selected filters.

---

## 🧠 Business-Context MoM Intelligence

The MoM indicators are designed around **business meaning**, rather than simply treating every increase as positive.

For example:

| KPI | Movement | Business Interpretation |
|---|---|---|
| Revenue | ▲ Increase | 🟢 Positive |
| Net Profit | ▲ Increase | 🟢 Positive |
| Profit Margin | ▲ Increase | 🟢 Positive |
| Total Trips | ▲ Increase | 🟢 Positive |
| Total Passengers | ▲ Increase | 🟢 Positive |
| Fuel Cost | ▲ Increase | 🔴 Negative |
| Operating Cost | ▲ Increase | 🔴 Negative |

This means the dashboard considers the nature of the KPI when determining whether a movement represents favourable or unfavourable performance.

---

## ⚙️ VBA Automation

VBA was implemented to improve dashboard automation and user experience.

The automation includes:

- Dynamic dashboard title
- Dynamic filter-context subtitle
- Automatic selected-filter display
- Automated MoM indicator updates
- Dynamic performance arrows
- Business-context MoM colour logic
- Dashboard text-box updates

---

## 🏗️ Technical Architecture

```text
Raw Transportation Data
          ↓
Data Preparation
          ↓
PivotTables
          ↓
Calculation / KPI Engine
          ↓
Interactive Slicers
          ↓
Dashboard Visualizations
          ↓
VBA Automation
          ↓
Executive Performance Insights
