# 🌱 Power BI Sustainability Project  

This repository documents my **6-day learning journey in Power BI**, built around a **sustainability and environmental** theme.  
The aim is to practice **data transformation, modeling, and visualization** while telling meaningful, data-driven stories on sustainability.  

---

## 📂 Repository Structure  
- **Day 1 – Urban Farming**  
  - `datasets/` → CSV/Excel datasets used  
  - `.pbix_file/` → Power BI report files  
  - `.png/` → Screenshots of dashboards and insight notes  

Subsequent folders (**Day 2–6**) will cover:  
- Data transformation  
- Data modeling  
- Advanced visualizations  
- Storytelling and dashboards  

---

## 🎯 Project Goals  
- Strengthen my Power BI skills in **data modeling, visualization, and basic transformation**  
  *(Note: I prefer handling most transformations and cleaning with Pandas or SQL before bringing data into Power BI.)*  
- Apply analytics to **real-world sustainability datasets**  

---

## 🌍 Day 1 – Urban Farming  
- Designed and generated a sample dataset: **`Urban_Farming.csv`**  
- Imported data into Power BI and explored the interface  
- Built a **basic visualization and insights dashboard** (`day1_visualization.png` and `day1_insights.png`)  
- Focus: city-level crop yields and production patterns  
<img width="500" height="400" alt="day1_visualization" src="https://github.com/user-attachments/assets/eab25b34-0135-4d9f-9db2-c28f815a69bd" />

---

## 🌳 Day 2 – Tree Planting Analysis  
- Developed a **star schema** with fact and dimension tables (Cities, Species, Tree_Planting)  
- Created key **DAX measures** (Total Trees, Avg Trees per Planting, CO₂ Absorption Estimate, % by Species)  
- Designed an interactive dashboard with region, city, and species breakdowns  
- **Key Insight:** Southwest region & Port Harcourt lead in planting efforts.
  
<img width="500" height="400" alt="day2_visualization" src="https://github.com/user-attachments/assets/c0a13be1-2ba9-47d7-a972-1c46e86de817" />
        
---
## 🌾 Day 3 – Climate & Agriculture Yield 
- Standardized and cleaned datasets.
- Modeled data into a star schema with fact and dimension tables.
- Created DAX measures for average rainfall, average temperature, total yield, and event-adjusted yield.
- Built visualizations to highlight climate trends, yield distribution, and correlations.

The focus for Day 3 was not only on building the dashboard but also on practicing **Data Storytelling**: translating visuals into meaningful insights.

<img width="500" height="400" alt="day3_dashboard" src="https://github.com/user-attachments/assets/655fc0ab-7f3d-48ac-8cbd-aa8a9593121f" />

### Day 3 insights.
Agricultural yields are heavily influenced by climate — rainfall, temperature, and extreme events. This analysis explores the relationship between climate factors (rainfall, temperature, and extreme weather events) and agricultural yield across regions from 2015–2024. The goal was to examine whether shifts in climate patterns are correlated with changes in crop productivity.

#### 📊 Key Visuals
- Area Chart – Average rainfall & temperature trends (2015–2024).
- Ribbon Chart – Total yield by crop type and year, showing shifts in dominant crops.
- Scatter Plots – Correlation of yield vs rainfall, and yield vs temperature.
- Combination Charts – Yield compared with rainfall/temperature alongside extreme events.
- Slicers – Filter by region and year to allow focused exploration.

The data shows clear patterns:
- **Rainfall & Yield** → Moderate rainfall years tended to produce higher yields, while years with extreme drought/flood events saw sharp declines.
- **Temperature & Yield** → Rising temperatures beyond certain thresholds correlated with reduced yields for sensitive crops.
- **Crop Trends** → Some resilient crops maintained steady yields, while others declined under adverse climate conditions.
- **Regional View** → Regions with better rainfall balance consistently outperformed drier or flood-prone regions.

In summary, the analysis reinforces that climate variability strongly impacts agricultural productivity, and adaptive crop planning is critical for sustainable farming.
