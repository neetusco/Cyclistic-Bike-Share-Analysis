# Cyclistic-Bike-Share-Analysis
Forecasting Demand and Understanding Rider Behavior for Strategic Growth

This project is part of a data-driven case study that explores rider behavior in Chicago's Divvy bike-share system. The goal is to understand differences between **casual riders** and **annual members**, and to forecast future bike demand using **Python**.

---

## Project Objectives

- Analyze riding behavior of **casual** vs. **member** users
- Conduct **geospatial analysis** to identify station usage patterns
- Apply **time series forecasting** (Prophet) to predict future demand
- Support **data-driven marketing strategies** to convert casual riders into annual members

---

## Dataset Source

- The data is provided by [Divvy Bike System](https://divvybikes.com/system-data), a public dataset released by **Motivate International Inc.**
- For this project, **12 CSV files (January to December 2024)** were used.
- The data includes fields such as: `ride_id`, `rideable_type`, `start_station`, `started_at`, `ended_at`, `member_casual`, etc.

---

## Tools & Libraries

- **Python**
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – data visualization
  - `Prophet` – forecasting
- **Jupyter Notebook** – analysis and visualization environment

---

## Key Analyses Performed

### 1. Data Cleaning & Preparation
- Combined 12 monthly CSV files into a single dataset
- Converted datetime columns
- Handled missing values and outliers

### 2. Geospatial Analysis
- Visualized station usage by **latitude & longitude**
- Color-coded by **user type** (casual vs member)
- Identified station demand hotspots

### 3. Time Series Forecasting
- Forecasted daily bike demand for next 30 days
- Separated forecasts by **user type**
- Analyzed **weekly and seasonal trends** using Prophet

### 4. Business Insights
- Casual riders peak on **weekends & summer months**
- Members ride more consistently on **weekdays**
- Recommendation: Target casual users with **seasonal offers** to drive conversions

---

## Sample Visualizations

![image](https://github.com/user-attachments/assets/387e2370-7088-4747-9a84-133392831f30)
![image](https://github.com/user-attachments/assets/91c046e2-8b63-48a4-bc94-20e4a92bfd32)
![image](https://github.com/user-attachments/assets/e5ac356c-ffed-483f-9560-e127406579f9)

---

## Challenges Encountered

- Handling large data (~5M rows) in memory
- Managing inconsistent datetime formats
- Forecasting uncertainty and seasonal alignment
- Visual clutter in station density maps

---

## Recommendations

- Launch **marketing campaigns before summer** to convert high-volume casual users
- Focus promotions on **weekends and tourist areas**
- Expand bike availability and maintenance resources in high-traffic months

---

## Author

**Neetika Upadhyay**  
Data Analyst  
Ottawa, Canada  
[neetusco26@gmail.com]

---

## 📄 License

This project is for educational purposes. Dataset is publicly available under Divvy’s data usage terms.

