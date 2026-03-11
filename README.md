# 🌿 Project 2 — EIA Environmental Data Dashboard

**Tools:** Python, pandas, matplotlib, seaborn  
**Datasets:** Air Quality (5,000 readings) | Water Quality (3,276 samples) 
| Global Air Quality (10,000 readings across 20 cities)  
**Target User:** Environmental Officers writing EIA Reports  

---

## 🎯 Project Objective
Analyse real environmental datasets across 4 key EIA parameters — 
Air Quality, Water Quality, Pollutant Correlations, and Global 
Benchmarking — to help environmental officers quickly identify 
risks before writing their EIA report.

---

## 🔍 Key EIA Findings

### 🌫️ Air Quality
- 17.1% of readings **exceed Malaysian DoE PM2.5 limit** of 35 µg/m³
- Maximum recorded PM2.5 was **295 µg/m³** — 8x the safe limit
- 10% of all readings classified as **Hazardous**
- Only 40% of readings classified as Good air quality

### 💧 Water Quality
- Only **39% of water samples are safe to drink**
- 44.5% of samples have **unsafe pH levels** outside 6.5–8.5 range
- Average pH of 7.08 — close to neutral but with dangerous extremes

### 🌍 Global Benchmarking
- **All 20 cities** in the global dataset exceed the DoE safe PM2.5 limit
- Dubai recorded the highest average PM2.5 at **80.0 µg/m³**
- Global average PM2.5 is more than double the safe threshold

### 🔗 Pollutant Correlations
- PM2.5 & PM10 show **0.97 correlation** — strongest relationship found
- CO & NO2 show **0.71 correlation** — both combustion-related gases
- Proximity to industrial areas **negatively correlates** with all pollutants
  — the closer to industry, the worse the air quality

---

## ⚠️ EIA Risk Flags Summary

| Parameter | Finding | Risk Level |
|---|---|---|
| PM2.5 Exceedance | 17.1% above DoE limit | 🟠 Medium-High |
| Max PM2.5 | 295 µg/m³ recorded | 🔴 Critical |
| Water Potability | 61% not safe to drink | 🔴 Critical |
| Unsafe pH | 44.5% outside safe range | 🟠 Medium-High |
| Global Cities | 20/20 exceed PM2.5 limit | 🔴 Critical |

---

## 📊 Visualisations

### Air Quality Distribution
<img width="1200" height="750" alt="air_quality_distribution" src="https://github.com/user-attachments/assets/0e6e233c-f7ba-4781-b721-48c1605a230d" />


### PM2.5 vs Malaysian DoE Limit
<img width="1500" height="750" alt="pm25_vs_limit" src="https://github.com/user-attachments/assets/9bd9fb62-114d-42dc-ba2c-dbecea44394a" />


### Water pH vs Safe Range
<img width="1500" height="750" alt="water_ph_distribution" src="https://github.com/user-attachments/assets/001813c2-639e-4692-a7f6-b693afc855da" />


### Water Potability
<img width="1050" height="1050" alt="water_potability" src="https://github.com/user-attachments/assets/a853e163-40e3-4bba-acc0-6d86e69929cf" />


### Pollutant Correlation Heatmap
<img width="1500" height="1200" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/15926457-20ae-45a0-9b48-065979300599" />


### Top 10 Most Polluted Cities
<img width="1500" height="900" alt="top10_polluted_cities" src="https://github.com/user-attachments/assets/4cacdfd6-f1ad-45bc-b193-f1fcb68c7afc" />


---

## 📁 Files
- `week2_eia_dashboard.ipynb` — Full analysis notebook
- [eia_dashboard.ipynb](https://github.com/user-attachments/files/25893022/eia_dashboard.ipynb)

---
*Tools: Python · pandas · matplotlib · seaborn*  
*Course: PeopleCert Data Science Foundation & Analyst*

