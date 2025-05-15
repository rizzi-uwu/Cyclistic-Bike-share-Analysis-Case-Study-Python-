# 🚴 Cyclists’ Historical Data Analysis

## 📌 Project Overview

This project provides a comprehensive analysis of cyclists' historical trip data from the **London Santander Cycle Hire Scheme** using public datasets. The goal is to uncover behavioral patterns, station popularity, seasonal variations, and other insights that help understand how London's citizens use bicycle-sharing services over time.

The dataset used is available via **Google BigQuery** and spans multiple years, offering millions of rows of real-time and historical trip data.

---

## 📊 Dataset Summary

The dataset includes:

- 📍 Start and End Station Names and IDs  
- ⏰ Start and End Timestamps  
- 🚴 Trip Duration (in seconds)  
- 🆔 Bike IDs  
- 📌 Station Metadata (location, identifiers)

Source: [London Bicycle Hires – Google BigQuery Public Dataset](https://console.cloud.google.com/marketplace/product/bigquery-public-data/london_bicycles)

---

## 🎯 Objectives

- Analyze trip durations over the years
- Identify top-performing and low-traffic stations
- Observe trends during specific dates or events
- Examine differences in ride behavior based on station or season

---

## 🛠️ Tools & Technologies

- **Google BigQuery**: To efficiently query massive datasets  
- **Python**: Analysis and scripting  
- **Pandas & NumPy**: Data wrangling  
- **Matplotlib, Seaborn, Plotly**: Visualizations (static and interactive)  
- **Jupyter Notebook**: Execution and documentation  

---

## 🔍 Key Questions Answered

- What were the longest and shortest trips recorded by year?
- Which stations were most frequently used?
- How do ride counts vary by season or day of the week?
- Which stations had the highest average ride durations?
- What insights emerge from specific historical dates (e.g. holidays, events)?

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/rizzi-uwu/Cyclists-Historical-Data-Analysis.git
cd Cyclists-Historical-Data-Analysis
