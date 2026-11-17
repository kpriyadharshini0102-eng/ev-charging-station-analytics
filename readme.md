# EV Charging Station Analytics

## Project Overview

This project analyzes electric vehicle (EV) charging session data to understand charging station utilization, energy consumption, waiting time, and operational performance.

The objective is to identify usage patterns, evaluate station performance, and provide actionable business recommendations to improve charging operations and customer experience.

## Business Problem Statement

As electric vehicle adoption increases, charging companies need to manage station utilization, energy demand, waiting times, and operational efficiency.

Without proper data analysis, it can be difficult to identify peak demand periods, understand customer charging behaviour, and recognize underperforming stations.

This project uses MySQL, Python, and Power BI to transform charging session data into meaningful business insights.

## Business Objectives

- Analyze total charging sessions and energy consumption.
- Evaluate charging station utilization.
- Identify peak and off-peak charging patterns.
- Analyze waiting time and charging duration.
- Compare performance across vehicle types.
- Identify high-performing charging stations.
- Provide recommendations to improve operational efficiency.

## Dataset Description

The dataset contains EV charging session information with 27 columns, including:

- Timestamp and station ID
- Location type
- Vehicle ID and vehicle type
- Arrival, charging start, and end times
- Waiting time and queue length
- Battery capacity and state of charge
- Energy consumed (kWh)
- Charging power and duration
- Station load and pricing
- Renewable energy ratio
- Traffic density and weather
- Demand and optimization-related information

Initial dataset size: 8,354 rows and 27 columns.

The final SQL analysis output contained 1,045 records.

## Tools and Technologies

- **MySQL:** Data validation, SQL queries, data analysis, and KPI extraction.
- **Python:** Data cleaning and analysis using Pandas, NumPy, and Matplotlib.
- **Power BI:** Interactive dashboard development and data visualization.
- **Excel:** Data inspection and validation where required.

## Project Workflow

1. Imported and inspected the charging session dataset.
2. Validated missing values, duplicate records, and data types using MySQL.
3. Prepared SQL queries to extract relevant business metrics.
4. Used Python for data cleaning and analysis.
5. Created KPI calculations and visualizations.
6. Developed a Power BI dashboard to communicate business insights.

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Charging Sessions | 1,045 |
| Total Stations | 20 |
| Total Vehicles | 1,045 |
| Total Energy Consumed | 39,540.74 kWh |
| Average Energy per Session | 37.84 kWh |
| Average Charging Duration | 176.80 minutes |
| Average Waiting Time | 9.60 minutes |
| Average Queue Length | 4.66 |

## Key Business Insights

1. The analysis covered 1,045 charging sessions across 20 charging stations.
2. Total energy consumption was 39,540.74 kWh.
3. Two-wheelers recorded 371 sessions, followed by cars with 341 and buses with 333.
4. Off-peak periods recorded 652 sessions, compared with 393 during peak periods.
5. Average waiting time was approximately 9.60 minutes across all sessions.
6. Stations ST012 and ST018 recorded the highest number of sessions, with 61 each.
7. ST005 recorded 59 charging sessions.

## Business Recommendations

- Monitor station utilization to identify opportunities for better resource allocation.
- Analyze peak-period demand to improve charging availability.
- Review waiting times and queue lengths to identify congestion.
- Evaluate vehicle-type demand when planning charging infrastructure.
- Monitor high-performing and low-performing stations to improve operational efficiency.
- Use energy consumption trends to support capacity planning.

## Dashboard Overview

The Power BI dashboard provides an overview of:

- Charging session KPIs
- Energy consumption
- Vehicle type analysis
- Peak versus off-peak performance
- Charging station performance
- Waiting time and charging duration

## Conclusion

This project demonstrates how SQL, Python, and Power BI can be used together to analyze EV charging operations and convert raw data into actionable business insights.

The analysis supports data-driven decisions related to charging station utilization, energy demand, waiting time, and operational efficiency.

**Tools:** MySQL | Python | Power BI
