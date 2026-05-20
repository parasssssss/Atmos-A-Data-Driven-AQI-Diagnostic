# Atmos: A Data-Driven AQI Diagnostic

## 📌 Project Overview
**Atmos** is an advanced environmental diagnostic analytics project that investigates the complex mechanics behind atmospheric pollution fluctuations in India. Built out of pure curiosity to understand why Air Quality Index (AQI) headlines experience rapid, aggressive spikes and sudden drops, this project processes **842,160 rows of ambient air quality data** inside Power BI to isolate uncontrollable environmental triggers from chronic manmade footprints.

---

## 🛠️ Tech Stack & Architecture
* **Data Volume:** 842,160 rows of continuous ambient air monitoring records
* **Analytics Platform:** Power BI Desktop
* **Data Modeling:** Star Schema design with optimized dimensional granularities
* **DAX Engineering:** Time-intelligence functions and dynamic context aggregations to prevent time-window skewing (e.g., separating seasonal averages from year-round totals).

---

## 📊 Key Insights & Analytics Breakdown

### 🌤️ The Environmental Triggers (Spikes & Drops)
1. **Temperature Inversion:** Dropping winter temperatures ($18^\circ\text{C}$) compress ground air into a heavy atmospheric lid, trapping everyday emissions right where we breathe.
2. **Precipitation Washout:** Rain acts as nature's ultimate physical air filter, slashing coarse dust ($PM_{10}$) by 54% and fine combustion soot ($PM_{2.5}$) by 51%.
3. **Planetary Boundary Layer:** Late afternoon solar drops shrink the atmospheric "ceiling," squishing urban evening rush-hour traffic exhaust right down to ground level.
4. **Wind Ventilation Threshold:** Gentle breezes under 10 km/h merely stir up dust and trap plumes, requiring a mechanical threshold of 10–12 km/h to actually flush pollution out.

### 🏭 The Manmade Fingerprints
1. **Stubble Burning vs. Local Industry:** Active crop fires spike Punjab (152.83) and Delhi (162.64), but Haryana’s extreme off-season baseline (236.34) proves its year-round heavy industrial dust completely eclipses seasonal smoke.
2. **The Festival vs. Baseline Reality:** Multi-year data reveals festival timelines form a steady floor, while chaotic hazardous spikes are driven by everyday economic volatility and weather traps.
3. **Traffic & Freight Logistics ($NO_2$):** Massive weekday commuter gaps expose white-collar transit, capped by an explosive 8:00 PM spike the exact hour heavy diesel freight trucks are legally allowed into city borders.
4. **Micro-Local Sourcing:** Gurugram’s staggering $PM_{10}$ dominance ($266.53\ \mu\text{g/m}^3$) exposes localized, unregulated construction dust, whereas coastal cities like Mumbai use natural sea breezes to constantly sweep particles away.

---

## 📈 Dashboard Architecture
The Power BI workbook is engineered across dedicated diagnostic perspectives:
* **Ambient Overviews:** High-level temporal tracking of global AQI movements.
* **Environmental Triggers:** Scatter plots and correlation matrixes mapping wind, rain, and temperature variations against pollutant density.
* **Manmade Fingerprints:** Granular analysis of chemical markers ($NO_2$, $CO$) alongside $PM_{2.5}$ and $PM_{10}$ ratios to trace industrial and logistical footprints.

---

## 🔬 Pollutant Reference Guide
* **$PM_{2.5}$:** Microscopic combustion smoke (crop fires/fuel) that penetrates deep into lungs.
* **$PM_{10}$:** Coarse construction and road dust that irritates eyes and throats.
* **$NO_2$:** Toxic diesel exhaust gas that acts as a direct tracker for heavy traffic gridlock.
* **$CO$:** Odorless gas from idling vehicles that cuts down oxygen levels in the blood.

---

## 💡 Strategic Takeaway
**Atmos** proves that rapid pollution spikes and drops are a highly predictable mix of meteorological thresholds and chronic human behavior. It demonstrates that temporary, seasonal policies cannot solve complex, year-round environmental crises—policy must address localized industrial and construction floors to achieve permanent relief.

---
*Developed by an Analyst who believes data doesn't lie, but demands we look past the headlines.*
