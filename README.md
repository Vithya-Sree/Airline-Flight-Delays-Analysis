# Root Cause Analysis of U.S. Aviation Bottlenecks using Python (2020–2026)

## Project Overview
This project analyses U.S. flight delay data from 2020 to 2026 to understand flight delay trends, airport and airline performance, major causes of delays, and flight disruptions.

Using Python, Pandas, Matplotlib, and Seaborn, the project explores flight operations and identifies key factors contributing to delays and cancellations.

## Objectives
1. **Flight Delay Trends:** Analyse flight delay patterns across different years and months.
2. **Airport and Airline Performance:** Identify airports and airlines with higher flight delay rates.
3. **Major Delay Causes:** Identify the major factors contributing to flight delays.
4. **Flight Disruptions:** Analyse delayed, cancelled, and diverted flights.
5. **Delay Duration Analysis:** Examine total flight delay duration across different causes.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning and Feature Engineering
- Handled missing values.
- Checked and handled duplicate records.
- Created new features to support analysis.
- Calculated delay rate and cancellation rate.
- Created cause-wise delay percentage features.
- Added a seasonal feature for trend analysis.

## Key Findings

1. **Flight Delay Trends**
   - Flight delay rate increased from **9.24% in 2020 to 22.06% in 2026**.
   - July recorded the highest monthly delay rate at **24.67%**, followed by June at **23.63%**.

2. **Airport and Airline Performance**
   - Fort Lauderdale Airport (FLL) recorded the highest airport delay rate at **23.31%**.
   - Frontier Airlines recorded the highest delay rate among the analysed airlines at **27.19%**.

3. **Major Delay Causes**
   - Late-aircraft and carrier-related issues were major contributors to flight delays.
   - Weather and National Aviation System (NAS) issues also contributed, while security-related delays had the smallest contribution.

4. **Flight Disruptions**
   - Delayed and cancelled flights showed a strong positive correlation of **0.89**.
   - Dallas/Fort Worth International Airport recorded the highest number of cancelled flights.

5. **Delay Duration Analysis**
   - Late-aircraft delays contributed approximately **153 million minutes** of delay duration.
   - The highest total delay duration was recorded in **2025, with 82.65 million minutes**.

## Conclusion
This project highlights the major factors affecting U.S. flight operations between 2020 and 2026. The analysis shows increasing delay rates, differences in airport and airline performance, and the significant impact of late-arriving aircraft.
