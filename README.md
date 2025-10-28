# UK Electricity Demand & Renewable Energy Dashboard

**Power BI Analytics Project**

This project analyzes electricity demand in England & Wales alongside renewable energy contributions and international energy trading. Using publicly available settlement data, the dashboard highlights the UK's evolving energy mix, renewable performance trends, and interconnector flow behavior.

---

## Dashboard Preview

![alt text](https://github.com/Alexandercheng-rsch/UK-Electricity-Demand-Dashboard/blob/main/1.png)
![alt text](https://github.com/Alexandercheng-rsch/UK-Electricity-Demand-Dashboard/blob/main/2.png)
---

## Objectives

- Measure total electricity demand over multiple years
- Understand growth and seasonality in renewable energy contribution
- Analyze cross-border electricity flows via key interconnectors
- Surface key metrics using dynamic KPIs and time-based visuals

---

## Data Engineering

Data was cleaned, consolidated, and enriched in Excel and Power BI.

**Data preparation tasks:**
- Merged multiple annual CSV files (approximately 800,000 rows)
- Standardized settlement periods and interconnector formats via Power Query
- Created time intelligence columns: Year, Month, Day, Week Number, Time, Settlement Period (1–288)
- Combined wind and solar generation into total embedded renewables
- Calculated renewable percentage contribution and net demand metrics

**Final dataset includes:**
- Grid demand metrics (England & Wales)
- Embedded wind and solar generation plus capacity
- Interconnector trading flows (IFA, IFA2, NEMO, East-West, BritNed, Moyle)
- Daily and intraday granularity for deep analysis

---

## Key Insights

- Electricity demand shows a reduction in recent years (aging consumption, efficiency improvements)
- Renewable energy share generally increasing, with strong year-on-year variation
- Major interconnectors show distinct import/export behavior depending on market conditions

---

## KPIs Displayed

- Peak England & Wales Demand
- Minimum Net Demand (high renewable plus import conditions)
- Average Renewable Percentage Contribution
- Maximum Trading Flow per Interconnector

---

## Visuals Included

- Bar and line chart: Demand vs Renewable Percentage across years
- Interconnector flow performance chart
- KPI cards for electricity demand, renewable performance, and interconnector flows

---

## Tools Used

- **Power BI** – Modeling, DAX metrics, visual analytics
- **Advanced Excel (Power Query & PivotTables)** – Data consolidation and preprocessing

---

## Repository Structure

```
├── energy_dashboard.pbix    # Main dashboard file
├── 1.png                    # Demo Image 1
├── 2.png                    # Demo Image 2
└── README.md                # Project documentation
```

---

## Future Improvements

- Directional split analysis: imports vs exports per interconnector
- Deeper weather impact correlation analysis (temperature, storms, etc.)
- Time-series forecasts for renewable penetration trends

---

## How to Use

Open the .pbix file in Power BI Desktop and explore insights via slicers and KPIs
