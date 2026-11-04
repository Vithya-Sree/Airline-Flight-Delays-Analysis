# Root Cause Analysis of U.S. Aviation Bottlenecks Using Python (2020–2026)

## Project Overview

This project focuses on analysing flight delays and operational bottlenecks in the U.S. aviation industry from 2020 to 2026.

Using Python and data visualization techniques, the project explores flight delay trends, airport and airline performance, major causes of delays, cancellations, diversions, and total delay duration.

The aim is to identify important patterns and understand the major factors contributing to flight delays.

## Project Objectives

1. Analyse flight delay trends across different years and months.
2. Compare flight delays and delay rates across airports and airlines.
3. Identify the major causes of flight delays.
4. Analyse the relationship between flight delays, cancellations, and diversions.
5. Analyse and compare flight delay durations across different causes and years.

## Dataset Information

- **Source:** U.S. Bureau of Transportation Statistics (BTS)
- **Industry:** U.S. Aviation
- **Time Period:** 2020–2026
- **Total Records After Cleaning:** 28,718
- **Original Columns:** 21
- **Final Columns After Feature Engineering:** 30

The dataset contains information about airlines, airports, arriving flights, delayed flights, cancellations, diversions, and different causes of flight delays.

## Tools and Technologies

- **Python:** Programming language used for data analysis.
- **Pandas:** Data cleaning, manipulation, and analysis.
- **NumPy:** Numerical calculations.
- **Matplotlib:** Data visualization.
- **Seaborn:** Statistical data visualization.
- **Google Colab:** Development environment.

## Project Workflow

1. **Data Collection:** Obtained U.S. flight delay data from the Bureau of Transportation Statistics.
2. **Data Understanding:** Examined the dataset using `head()`, `tail()`, `shape`, `columns`, `info()`, and `describe()`.
3. **Data Cleaning:** Identified and handled missing values and checked duplicate records.
4. **Feature Engineering:** Created additional features to support further analysis.
5. **Exploratory Data Analysis:** Examined the dataset to understand patterns and distributions.
6. **Data Visualization:** Created charts to identify trends, comparisons, and relationships.
7. **Insights and Recommendations:** Interpreted the results and identified possible areas for operational improvement.

## Feature Engineering

The following additional columns were created to support the analysis:

| Feature | Description |
|---|---|
| `delay_rate` | Percentage of flights delayed |
| `cancellation_rate` | Percentage of flights cancelled |
| `avg_delay_duration` | Average delay duration |
| `carrier_share` | Carrier-related share of delays |
| `weather_share` | Weather-related share of delays |
| `nas_share` | NAS-related share of delays |
| `security_share` | Security-related share of delays |
| `late_aircraft_share` | Late-aircraft-related share of delays |
| `season` | Season based on the month |

## Analysis and Visualizations

### 1. Flight Delay Trends
- Analysed yearly flight delay rates.
- Compared monthly flight delay rates.
- Used a heatmap to examine monthly delay patterns across years.

### 2. Airport and Airline Performance
- Identified the top 10 airports by flight delay rate.
- Identified the top 10 airlines by flight delay rate.
- Compared airport and airline performance using horizontal bar charts.

### 3. Major Causes of Flight Delays
- Compared the total number of delays caused by carrier issues, weather, NAS, security, and late aircraft.
- Identified the major contributors to flight delays.

### 4. Flight Delays, Cancellations, and Diversions
- Examined the distribution of on-time, delayed, cancelled, and diverted flights.
- Analysed monthly flight disruptions.
- Examined the relationship between delayed and cancelled flights across airports.

### 5. Flight Delay Duration Analysis
- Compared total delay minutes by cause.
- Analysed yearly delay duration across different causes using a heatmap.
- Compared average delay duration by cause.

## Key Findings

- Flight delay rates increased from **9.24% in 2020 to 22.06% in 2026**.
- July recorded the highest monthly delay rate at **24.67%**.
- Fort Lauderdale-Hollywood International Airport had the highest delay rate among the selected airports at **23.31%**.
- Frontier Airlines recorded the highest delay rate among the selected airlines at **27.19%**.
- Late Aircraft was the leading cause by number of delays, contributing **1,877,404 delays**.
- A strong positive correlation of **0.89** was observed between delayed and cancelled flights across airports.
- Late Aircraft contributed the highest total delay duration, with **153,076,879 minutes**.

## Business Insights

- Improve aircraft turnaround procedures to reduce late-aircraft-related delays.
- Review flight schedules during periods with higher delay rates.
- Improve coordination between airlines, airports, and air traffic management.
- Strengthen contingency planning to manage cancellations and other flight disruptions.
- Focus on major delay causes to improve operational efficiency.

## Conclusion

This project uses Python-based data analysis and visualization to identify flight delay patterns and major operational bottlenecks in the U.S. aviation industry.

The analysis provides useful insights into delay trends, airport and airline performance, and the major causes of flight disruptions. These findings can support better operational planning and decision-making.

## Author

**Data Analytics Project**

