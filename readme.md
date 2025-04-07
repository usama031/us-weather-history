# US Weather History Analysis 🌦️

This project analyzes historical weather data in the United States to uncover patterns, trends, and insights. The dataset includes daily weather observations from a specific location (e.g., Minneapolis–St. Paul International Airport) and covers several years of data. It is a great dataset for exploring time series analysis, feature engineering, and data visualization in data science.

---

## 📊 Dataset Overview

The dataset typically contains the following features:

- `Date`: The date of the observation.
- `ActualMeanTemp`: The observed mean temperature.
- `ActualMinTemp`: The observed minimum temperature.
- `ActualMaxTemp`: The observed maximum temperature.
- `AverageMinTemp`: Historical average minimum temperature.
- `AverageMaxTemp`: Historical average maximum temperature.
- `RecordMinTemp`: Record low temperature for that date.
- `RecordMaxTemp`: Record high temperature for that date.
- `Precipitation`: Observed precipitation on that day.

---

## 🔍 Project Objectives

- Perform **Exploratory Data Analysis (EDA)** to identify temperature trends, anomalies, and seasonal behavior.
- Compare **actual temperatures** with **historical averages** and **record temperatures**.
- Visualize **precipitation trends** and understand the distribution of rainfall over time.
- Prepare features for machine learning models to potentially **forecast weather patterns**.

---

## 📂 Project Structure

```bash
us-weather-history/
├── data/
│   └── weather.csv                 # Raw dataset
├── notebooks/
│   └── eda_weather.ipynb          # Jupyter notebook with analysis
├── plots/
│   └── temperature_trends.png     # Output visualizations
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
git clone https://github.com/usama031/us-weather-history.git
