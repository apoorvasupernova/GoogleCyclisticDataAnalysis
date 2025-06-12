# Cyclistic Bike-Share Data Analysis (Q1 2019 vs Q1 2020)

This project uses R and tidyverse libraries to analyze Cyclistic's bike-share data from Q1 2019 and Q1 2020. The goal is to uncover usage patterns between **casual riders** and **members**, enabling strategic decisions for marketing and operations.

---

## 📁 Dataset Sources
- `Divvy_Trips_2019_Q1.csv`
- `Divvy_Trips_2020_Q1.csv`

These datasets contain trip-level details, including timestamps, station locations, and rider types.

---

## 📊 Key Objectives

- Clean and combine the 2019 and 2020 datasets.
- Standardize column names and values for consistency.
- Engineer features like ride length, weekday, and date parts.
- Filter out quality check/test rides and erroneous data.
- Perform descriptive and comparative analysis between rider types.
- Visualize differences in ride frequency and duration.
- Export summary data for further analysis.

---

## 🛠 Tools & Libraries
- **R**
- **Tidyverse** (`dplyr`, `ggplot2`, `readr`, etc.)
- **Conflicted** for conflict resolution in functions
- R Markdown for reproducibility

---

## 🚀 Project Workflow

1. **Load Libraries & Data**
2. **Standardize Column Names**
3. **Merge Quarterly Data**
4. **Clean & Prepare Dataset**
   - Remove unnecessary columns (e.g., lat/long, birthyear)
   - Recode user types to align formats
   - Remove invalid or negative-duration rides
5. **Feature Engineering**
   - Create `ride_length`, `weekday`, `month`, etc.
6. **Descriptive Statistics**
   - Mean, median, max, and min ride times
7. **Comparative Analysis**
   - Between casual vs member users
   - By day of the week
8. **Data Visualization**
   - Ride counts and durations by weekday and user type
9. **Export Output**
   - Save summarized ride length averages to CSV

---

## 📈 Sample Insights

- Members typically ride more frequently on weekdays.
- Casual riders show higher average ride durations, especially on weekends.
- Clear behavioral differences emerge in both timing and ride length across user groups.

---

## 📤 Output

A summary CSV file is generated:
__avg_ride_length.csv__
This contains average ride durations grouped by rider type and weekday for further insights.

---

## 📌 Note

This project is part of the **Google Data Analytics Capstone**: "Cyclistic Bike-Share Case Study". The insights can help the company convert casual riders into members.

---