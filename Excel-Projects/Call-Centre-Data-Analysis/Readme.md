# Call Centre Analytics Dashboard

## Project Overview  
This Excel dashboard analyzes call centre performance by integrating two datasets—Calls and Customers—using Power Query, 
Power Pivot, and Pivot Charts. The dashboard reveals trends in call volume, agent performance, sales conversion, and customer demographics.

## Objective & Process

### 1. Data Preparation & Modeling
- Imported two tables: *Calls* (with timestamp, duration, purchase, rating, agent) and *Customers* (with demographics).
- Cleaned the data by removing duplicates and checking data types.
- Connected both datasets via *Customer ID* using Power Pivot.

### 2. Pivot Table Metrics
- Extracted insights with Pivot Tables, including:
  - Call counts by month and day of week
  - Calls and revenue by representative
  - Average satisfaction and 5‑star ratings
  - Customer demographics breakdown (city and gender)
- Computed summary values: Total Calls, Total Purchase Amount, Average Rating, 5-Star Calls, and Total Duration.

### 3. Dashboard Design
- Built interactive Pivot Charts to visualize metrics.
- Included slicers to filter by representative, updating all charts and KPI cards simultaneously.
- KPI cards display summary values across key metrics.

---

## Dashboard Features
- **KPI Highlights**: Total Calls, Total Sales, Average Rating, 5‑Star Calls, Total Duration  
- **Visualizations**:
  - Monthly call trends
  - Weekday call distribution
  - Agent performance comparison (calls & sales)
  - Customer demographics by city and gender  
- **Interactive Slicers**: Agent filters that update charts and KPIs dynamically

---

## Tools & Technologies
| Tool             | Usage                           |
|------------------|------------------------------   |
| Excel            | Data handling and visualization |
| Power Query      | Importing and cleaning data     |
| Power Pivot      | Establishing table relationships|
| Pivot Tables     | Calculating metrics             |
| Pivot Charts     | Representing data visually      |
| Slicers          | For dynamic filtering           |

---

## Insights & Recommendations
- Identified peak call periods (by month and weekday) to inform optimized staffing.
- Highlighted high-performing and lower-performing agents for recognition and training.
- Mapped demographic hotspots (cities and gender) for targeted engagement.
- Analyzed purchase revenue per agent to inform potential sales coaching and incentives.

---

##  How to Use
1. Clone or download the repository.
2. Open `CallCentreAnalysisProject.xlsx`.
3. Navigate through the sheets:
   - **Data**: Cleaned and raw dataset
   - **Pivot**: Calculations driving the metrics
   - **Dashboard**: Interactive visuals with slicers

---



