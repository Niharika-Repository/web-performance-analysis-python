# Website Performance Analysis (Python)

Exploratory data analysis(EDA) of website analytics data focusing on traffic, engagement, and channel performance.

---

## Overview
This project analyzes website analytics data to understand **traffic distribution, engagement behavior, and channel-level performance** across time. The analysis focuses on identifying patterns in user activity and engagement using hourly data and standard web analytics metrics.

---

## Dataset
The dataset consists of **3,183 records** collected at an **hourly level of granularity** (`YYYYMMDDHH`). Each record represents website activity aggregated by **Session Primary Channel Group** for a given hour.

The data contains standard web analytics metrics related to user activity, session behavior, engagement, and event interactions. This structure supports analysis of **time-based trends**, **channel comparisons**, and **engagement patterns** across different periods of the day.

---

## Methodology

### Data Preparation
- Loaded raw CSV data using Pandas  
- Removed non-data and metadata rows  
- Standardized column names  
- Converted session and engagement fields to numeric data types  
- Extracted hour-level features from timestamp values  

---

### Analysis Performed
- Hourly traffic trend analysis  
- Channel-wise comparison of users, sessions, and engaged sessions  
- Engagement rate and engaged sessions per user analysis  
- Hour-by-channel heatmap analysis  
- Time-based engagement trend analysis  

---

### Visualization
- Line charts for traffic and engagement trends  
- Bar charts for channel-level comparisons  
- Heatmaps for hourly traffic distribution  
- Engagement trend plots for performance monitoring  

---

## Key Findings
- Website traffic is concentrated during specific hours rather than evenly distributed  
- Some channels generate high traffic volume but lower engagement levels  
- Certain channels show stronger engagement despite lower traffic volume  
- Engagement metrics vary by time of day, indicating clear peak interaction periods  

---

## Business Insights
- Traffic volume alone is not sufficient to measure performance  
- Engagement metrics provide better visibility into channel effectiveness  
- Time-based analysis helps identify optimal periods for campaigns and content  
- Channel-level engagement differences highlight optimization opportunities  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Next Steps
- Include conversion or revenue-related metrics  
- Segment users into new and returning groups  
- Build an interactive dashboard using BI tools  
- Automate the analysis for periodic reporting  
