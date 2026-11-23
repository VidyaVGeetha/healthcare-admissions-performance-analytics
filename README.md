# Healthcare Admissions & Performance Analytics

**Power BI | Data Analysis | Power Query | DAX | Time-Series Forecasting**

## Project Overview

An end-to-end healthcare data analytics project developed using Microsoft Power BI to explore hospital admissions, patient demographics, departmental performance, seasonal trends and operational indicators.

The project covers data preparation, transformation, data modelling, DAX calculations, interactive dashboard development and time-series forecasting using historical admission data from 2022–2024.

It also includes a deeper investigation of repeat-patient admission activity using Power Query grouping, filtering and table joins.

## Business Objectives

- Analyse hospital admission trends over time.
- Explore patient demographics and admission patterns.
- Compare departmental admission performance.
- Identify seasonal variations in hospital admissions.
- Investigate waiting times and length of hospital stays.
- Examine treatment costs and repeat-patient admission activity.
- Forecast future monthly admissions using historical trends.

## Tools & Technologies

| Technology | Application |
|---|---|
| Power BI Desktop | Interactive dashboards and reporting |
| Power Query | Data cleaning, transformation and merging |
| DAX | Measures, calculations and KPIs |
| Excel | Dataset preparation and exploration |
| Power BI Forecasting | Monthly time-series forecasting |

## Dataset Overview

The project uses a demonstration dataset containing:

- 650 hospital admission records
- 500 unique patients
- Three years of data (2022–2024)

The dataset includes patient demographics, admission and discharge dates, departments, diagnosis categories, waiting times, length of stay, treatment costs and discharge outcomes.

## Data Preparation & Transformation

Power Query was used to prepare and investigate the data through:

- Data inspection and validation.
- Data cleaning and transformation.
- Creating and preparing analytical queries.
- Grouping records by Patient ID to calculate admission counts.
- Filtering patients with more than one admission.
- Merging queries using Patient ID.
- Using an Inner Join to match repeat-patient records with the original admissions data.
- Expanding relevant admission details, including Admission ID, Department and Admission Year.
- Filtering and grouping the resulting records to analyse repeat-patient admissions by department.

This process helped investigate admission activity involving patients with multiple admissions.

## Dashboard Pages

### 1. Admissions Overview
- Total admissions and unique patient KPIs.
- Total treatment costs and average length of stay.
- Monthly admission trends (2022–2024).
- Monthly comparisons across years.
- Seasonal admission analysis.
- Department and patient demographic breakdowns.
- 2025 monthly admissions forecast with confidence intervals.

- <img width="1206" height="670" alt="image" src="https://github.com/user-attachments/assets/c02bcdc9-0fe7-49c7-9fa0-a13a0b54133a" />



### 2. 2024 Admissions Analysis
- Analysis of 2024 admission volumes.
- Department-level admission comparisons.
- Identification of departments with the highest admission activity.

### 3. Department Performance
- Admissions across hospital departments.
- Departmental comparisons.
- Average waiting time by department.

### 4. Winter Analysis
- Winter admissions by department.
- Winter admissions by age group.
- Identification of departments and age groups contributing most to winter admissions.

- <img width="1206" height="370" alt="image" src="https://github.com/user-attachments/assets/41250579-4ceb-4648-89ee-575ffb07e979" />



## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Admissions | 650 |
| Unique Patients | 500 |
| Total Treatment Cost | £2.60M |
| Average Length of Stay | 3.29 days |

## Key Findings

- Winter recorded the highest number of admissions (202), while summer recorded the lowest (143).
- General Medicine recorded the highest overall admissions (164).
- December had the highest historical monthly admissions (77).
- Oncology recorded the highest average waiting time (10.15 days), while Orthopaedics recorded the lowest (5.62 days).
- In 2024, General Medicine had the highest departmental admissions (60), followed by Orthopaedics (51) and Respiratory (47).
- During winter, General Medicine recorded the highest departmental admissions (46).
- The 0–17 age group recorded the highest winter admissions (50), followed by the 75+ age group (44).
- The repeat-patient investigation identified admission records associated with patients who had multiple admissions during 2024, across all six departments.

## Time-Series Forecasting

A monthly admissions forecast was developed using historical data from 2022–2024.

The forecast extends into 2025 and includes:

- Historical monthly admission trends.
- Forecasted admission values.
- Confidence intervals illustrating forecast uncertainty.

This demonstrates the use of historical trends to explore potential future hospital admission patterns.

## Skills Demonstrated

- Data cleaning and transformation
- Power Query and query management
- Group By and conditional filtering
- Merge Queries and Inner Joins
- Data modelling and relationship analysis
- DAX measures and KPI development
- Interactive dashboard development
- Trend and seasonal analysis
- Time-series forecasting
- Business insight communication

## Data Disclaimer

This is a demonstration project using synthetic healthcare data created for learning and portfolio purposes. It does not contain real patient information and should not be interpreted as official NHS statistics.

## Project Objective

To demonstrate end-to-end data analyst capabilities through practical data preparation, investigation, transformation, analytical modelling, dashboard development and forecasting.

---
