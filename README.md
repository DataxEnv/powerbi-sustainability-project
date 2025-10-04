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
Agricultural yields are heavily influenced by climate — rainfall, temperature, and extreme events. This dashboard explores how climate patterns over the past decade have shaped agricultural yields across regions. The goal was to examine whether shifts in climate patterns are correlated with changes in crop productivity.

### 📊 Key Visuals & Insights

#### 1.  Climate Trends Over Time  
*Area Chart* – Rising average temperatures alongside **declining rainfall**.  
- A brief rainfall spike appears in 2018, but the long-term trend points downward.  
- Temperatures climb steadily, signaling a **hotter, drier climate**.  
 **Impact:** Farmers face less water and more heat, both of which threaten stable food production.

#### 2.  Crop Yield Leaders  
*Ribbon Chart* – Cereals consistently dominate yields, followed by legumes and root/tuber crops.  
- Yield levels fluctuate in response to rainfall and temperature shifts.  
 **Impact:** Cereals remain resilient, but legumes (which need stable rainfall) show higher vulnerability.  

#### 3.  Rainfall vs Yield  
💧 *Scatter Plot* – A **positive correlation** emerges: as rainfall increases, yields rise. The regression line slopes upward, showing that water availability directly supports food output.  
- Rainfall above ~1100 mm tends to push yields closer to **150K**.  
- Lower rainfall years cluster around **135K–140K** yields.  


#### 4.  Temperature vs Yield  
🔥 *Scatter Plot* – A **negative correlation** is clear: The downward-sloping regression line shows that higher temperatures lead to lower yields.
- Once average temperatures cross **228–230°C**, yields consistently fall below **140K**.  


#### 5.  Extreme Events & Yield Performance  
*Column-Line Combo Chart* – The effect of droughts, floods, and heatwaves.  
- Yields dip sharply during **drought years**.  
- Rainfall fluctuations add another layer of instability.  
   **Impact:** Farmers aren’t just battling averages — it’s the *spikes and shocks* that devastate harvests.  


### Conclusion  
- Rainfall strongly supports yield growth.  
- Rising temperatures undermine food security.  
- Extreme events intensify risks, driving volatility in farming outcomes.  
- Cereals dominate yields but climate pressures may challenge this resilience over time.  



