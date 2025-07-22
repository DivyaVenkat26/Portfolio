#  MTA Ridership Analysis Dashboard

## Project Overview  
An interactive Excel dashboard analyzes New York’s MTA Ridership dataset using Power Query, Pivot Tables, forecasting tools, and slicers. It explores transit trends across multiple modes, examines pandemic-era patterns, and forecasts future subway usage to support recovery planning.

---

## Objective & Approach

### 1. Data Cleaning & Preparation (Power Query)  
- Imported the MTA dataset and removed duplicates or inconsistencies.  
- Derived time-based fields:  
  - **Day Name** (Monday, Tuesday…)  
  - **Day Type** (Weekday or Weekend)  
- Added calculated columns:  
  - **Total Ridership** (sum across transit modes)  
  - **Subway to Bridges & Tunnels Ratio**

### 2. KPI & Metric Calculations (Formulas & Pivot Tables)  
- Calculated key metrics:  
  - Total days, weekdays, weekends  
  - Subway ridership percentage  
  - Correlation between subway & bus ridership  
  - Highest subway and lowest bus ridership days  
  - Total ridership  
- Created Pivot Tables to analyze:  
  - Average ridership by mode  
  - Ridership share per mode  
  - Average ridership by month  
  - Trends in Access‑A‑Ride vs Metro‑North  
  - Correlation between subway and bus usage  
  - Moving average for long‑term trend detection  
  - Post-pandemic recovery patterns

### 3. Forecasting Analysis  
- Crafted an Excel Forecast Sheet projecting subway ridership for the next three months.  
- Incorporated forecast results into the dashboard for comparison with actual data.

### 4. Dashboard Development (Pivot Charts & Slicers)  
- Built interactive Pivot Charts displaying usage patterns by day, month, and year.  
- Added KPI cards for quick metrics visibility.  
- Included slicers for dynamic filtering by month and year, updating all visuals simultaneously.

---

## Key Dashboard Features  
- **Interactive Visuals**:  
  - Daily, monthly, yearly ridership trends  
  - Pandemic recovery comparison  
  - Ridership correlation and moving averages  
- **KPI Cards**:  
  - Total Ridership  
  - Subway Ridership Percentage  
  - Subway & Bus Correlation Coefficient  
  - Highest & Lowest Ridership Stats  
  - Total Weekday/Weekend Counts  
- **Dynamic Filtering**:  
  - Pivot Slicers for Month and Year

---

## Tools & Technologies  
- **Excel Power Query**: Data cleaning & transformation  
- **Pivot Tables & Pivot Charts**: Analysis & visualization  
- **Excel Formulas**: KPI and metric computations  
- **Forecast Sheet**: Ridership trend forecasting  
- **Slicers**: Dashboard interactivity

---

## Insights & Recommendations  
- Documented pandemic impact and monitored gradual recovery across transit modes.  
- Identified key trends by transit type, day, and timeframe, including weekday/weekend differences.  
- Forecasted subway ridership to guide future transit capacity planning.  
- Provided actionable insights into transit system recovery post-pandemic.

---


