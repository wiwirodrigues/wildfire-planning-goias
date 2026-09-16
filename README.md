# wildfire-planning-goias
Interactive Business Intelligence dashboard for wildfire prevention planning in Brazil - Goiás State Parks.

# 🛰️ Wildfire Prevention Planning in Goiás State Parks: A Business Intelligence Tool
> **Support for Wildfire Prevention Planning in Goiás State Parks Based on Hotspots**

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Cerrado](https://img.shields.io/badge/Biome-Cerrado-green?style=for-the-badge)
![CBMGO](https://img.shields.io/badge/Domain-Wildfire%20Management-red?style=for-the-badge)

---

## 📌 About the Project
This project presents an interactive **Business Intelligence (BI)** dashboard designed to support strategic planning and preventive actions against wildfires in the state parks of Goiás, Brazil[cite: 2]. 

Using historical georeferenced hotspot data from **2016 to 2025**[cite: 2], the tool helps decision-makers identify critical areas, analyze fire recurrence patterns, and optimize the allocation of operational resources for environmental protection.

---

## 🔍 Key Findings & Ecological Insights
* **The Core Question:** *How long does it take for a burned area in the Cerrado to burn again?*
* **Statistical Discoveries:** 
  * **Historical Average (Hotspot Recurrence Interval - IRFC):** ~3.05 years[cite: 2].
  * **Statistical Mode (Peak Frequency):** **2 years** (representing 25.9% of all reburn events)[cite: 2].
* **The Ecological Factor:** The Cerrado biome features a high density of grasses and herbaceous vegetation (fine fuels) with rapid biomass reconstitution capacity[cite: 2], explaining why the vast majority of reburns (87.2%) occur within a 4-year window[cite: 2].

---

## 📊 The Power BI Dashboard
To transform raw satellite telemetry into actionable insights, an interactive dashboard was built using **Microsoft Power BI**[cite: 2].

### Dashboard Features:
* **Interactive Map (`Azure Maps`):** Spatial visualization of historical hotspots (2016–2025) categorized chronologically by year[cite: 2].
* **Dynamic Filters:** Filter data effortlessly by `Year`, `Month`, and specific `Parks`[cite: 2].
* **Real-time Metrics (`Total Hotspots`):** Instant aggregation of fire focus points based on customized user filters[cite: 2].

> *🔗 **Access Link:** [Insert your published Power BI web link here]*

---

## 📂 Data Sources & Methodology
The data pipeline relies entirely on trusted open-source environmental monitoring data:
* **Hotspot Data:** Acquired from the **BDQueimadas Program** provided by the National Institute for Space Research (**INPE**), utilizing the Suomi-NPP satellite (VIIRS sensor, 375m resolution)[cite: 2].
* **Protected Areas:** State park boundaries obtained from the State System of Environmental Geoinformation (**SIGA**)[cite: 2].
* **Analytical Approach:** Spatial joining and calculation of recurrence intervals (*IRFC*) to indirectly infer biomass accumulation patterns and potential fire severity[cite: 2].

---
*Developed as a technical solution for wildfire risk management and operational planning.*
