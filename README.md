Overview

This project performs structured time-series analysis on the WHO Global COVID-19 Dataset using Python and Pandas.
The objective of this project is to clean, filter, and aggregate large-scale epidemiological data to extract meaningful temporal and regional patterns during the COVID-19 pandemic (March 2020 – August 2023).
This project focuses strictly on descriptive time-series analytics and data aggregation, not predictive modeling.

Dataset

Source: WHO Global COVID-19 Dataset
Time Period Considered: 1 March 2020 – 31 August 2023
Final Filtered Dataset Size: 306,960 rows × 5 columns

Key Variables Used:

Date_reported
Country
WHO_region
New_cases
New_deaths
Cumulative_cases

Tools & Technologies

Python
Pandas
Google Colaboratory (Google Colab)

Analysis Performed

Data Preprocessing
CSV import and validation
Date conversion to datetime format
Time-range filtering
Column subsetting

Country-Level Analysis

Identified Top 5 countries by cumulative case count
Highest: United States (103M+ cases)

Global Daily Aggregation

Computed worldwide daily new case counts
Identified peak infection date:
30 January 2022
~8.4 million global cases (single-day peak)

Quarterly Aggregation

Converted dates into quarterly periods
Aggregated total cases and deaths by quarter
Observed sharp case escalation during late 2020 and 2021 waves

Regional Analysis

Computed total cases by WHO region
European region reported the highest cumulative case count

Monthly Pivot Table

Constructed region-wise monthly comparison
Identified synchronized global surge patterns (especially during Omicron wave)

Key Findings

COVID-19 case burden was highly concentrated among a few major countries.
The European region recorded the highest cumulative cases.
The largest global daily spike occurred on 30 January 2022.
Time-based aggregation reveals distinct pandemic wave patterns.

Future Improvements

Rolling average smoothing
Mortality rate analysis
Growth rate modeling

ARIMA/Prophet-based forecasting

Visualization using Matplotlib or Seaborn
