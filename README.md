## Project Title
# Indian-Railways-Report
# Operations and Train Traffic Analysis Dashboard

# Problem Statement
Indian Railways operates one of the largest and most complex railway networks in the world, managing thousands of trains, stations, zones, and passenger classes every day. Due to the vast scale of operations, decision-makers face challenges in:

- **Monitoring train traffic efficiently across different railway zones and states**

- **peak departure hours and train distribution by distance**

- **Analyzing station density and zone-wise operational load**

- **Identifying dominant train types and passenger class utilization**

- **Gaining a consolidated, real-time view of key operational KPIs**

The absence of a centralized, visual analytics system makes it difficult to derive actionable insights from raw railway data, leading to inefficiencies in planning, scheduling, and resource allocation.

This project aims to address these challenges by developing an interactive Power BI dashboard that transforms Indian Railways operational data into meaningful insights, enabling data-driven decision-making for traffic management, infrastructure planning, and service optimization

# Objectives
- **To design an interactive Power BI dashboard that provides a consolidated view of Indian Railways operational data.**

- **To analyze overall train operations by tracking total trains, railway zones, stations, express trains, average distance covered, and traffic percentage.**

- **To identify train distribution across distance ranges in order to understand short-haul and long-haul service patterns.**
**
- **To examine hourly train departure trends and highlight peak traffic hours for better scheduling and congestion management.**

- **To visualize state-wise distribution of railway stations using map-based insights for infrastructure planning.**

- **To analyze train types (Passenger, Express, Superfast, MEMU, etc.) and determine their contribution to total operations.**

- **To evaluate railway zone-wise categorization and compare operational load across different zones.**

- **To study passenger class distribution (Sleeper, AC, Chair Car, First Class) to understData Modelingand travel class preferences.**

- **To support data-driven decision-making for optimizing railway operations, improving passenger services, and enhancing capacity planning.**

# Tools & Technologies
- Python (Pandas Library)
- Power Query (M Language)
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Excel / CSV Files
- Data Modeling
- Map Visualizations (Power BI Map / Bing Maps)

# Steps Followed
### 1. Dataset Download
- Downloaded the Indian Railways operations dataset in **CSV format** from **Kaggle**. 

---

### 2. Data Cleaning & Preprocessing (Python)

- **Opened the dataset in Jupyter Notebook.**

- **Used the Pandas library to:**

Remove duplicate records.

Handle missing and null values.

Standardize column names and formats.

Correct data types (dates, numeric values, categorical fields).

Validate data consistency and integrity. for faster processing.
