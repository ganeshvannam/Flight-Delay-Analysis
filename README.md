# ✈️ Flights Delay Analysis Project


## 📌 Overview
This project analyzes flight delay patterns at three major connector airports:
- **ORD**: [Chicago O'Hare International Airport](https://en.wikipedia.org/wiki/O%27Hare_International_Airport)
- **DTW**: [Detroit Metropolitan Airport](https://en.wikipedia.org/wiki/Detroit_Metropolitan_Airport)
- **MSP**: [Minneapolis-Saint Paul Airport](https://en.wikipedia.org/wiki/Minneapolis%E2%80%93Saint_Paul_International_Airport)

We explore historical flight data to assess operational reliability, identify delay trends, and provide actionable insights to stakeholders in the aviation industry.

---

## 📂 Data Source
**US Department of Transportation**  
🔗 [Bureau of Transportation Statistics (BTS)](https://www.bts.gov/)  
Includes:
- Flight schedules
- Actual departure/arrival times
- Cancellations & diversions
- Delay causes (weather, carrier, etc.)

---

## 🔍 Key Analysis Tasks

### 1. Data Preparation
- 🧹 Data cleaning & preprocessing: Handled missing values, outliers, and out-of-range values using advanced techniques.
- ❌ Filtered out cancelled/diverted flights to ensure accurate analysis.
- ⏳ Engineered time-related features (e.g., flight delay duration, time of day) to gain deeper insights into delay patterns.

### 2. Exploratory Analysis
- 📊 Flight volume trends: Identified peak flight times for all airports, providing insights into airport congestion.
- 🚩 Cancellation impact analysis: Assessed the correlation between cancellations and delays, contributing to more effective operational planning.
- 📉 Delay distribution statistics: Visualized the spread and frequency of flight delays, helping identify major problem areas.

### 3. Advanced Insights
- 📅 Temporal patterns (weekly/monthly trends): Unveiled seasonal fluctuations and time-of-day impacts on delays.
- 🥇 Top 10 worst-performing aircraft: Analyzed aircraft-specific performance, enabling focused maintenance and performance improvements.
- ⚠️ Longest delay incidents analysis: Investigated extreme delays, uncovering potential causes like weather disruptions or scheduling inefficiencies.

---

## 📊 Key Metrics Analyzed
- **Departure/Arrival Delay Distributions**: Gained insights into delay patterns to help optimize flight schedules.
- **Average Delay Times by Airport**: Compared performance across airports to evaluate operational efficiency.
- **Carrier Performance Comparison**: Identified underperforming carriers for potential partnerships or improvements.
- **Hourly Delay Trends**: Mapped delays to specific hours of the day to optimize scheduling and resource allocation.
- **Monthly Delay Patterns**: Examined monthly trends to identify peak disruption periods, aiding in better resource forecasting.

---

## 🛠️ Technical Stack
| Category        | Tools/Libraries       |
|-----------------|-----------------------|
| Data Processing | pandas, numpy         |
| Visualization   | matplotlib, seaborn    |
| Date Handling   | datetime              |
| Environment     | Jupyter Notebook       |

---

## 📈 Key Achievements
- Developed actionable insights that can assist airports in improving operational efficiency and reducing delays.
- Designed and implemented visually appealing charts and graphs to present findings to non-technical stakeholders.
- Demonstrated proficiency in Python and popular data science libraries, showcasing skills in both data cleaning and visualization.


