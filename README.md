# wildfire-planning-goias
Interactive Business Intelligence dashboard for wildfire prevention planning in Brazil - Goiás State Parks.

# 🛰️ Wildfire Prevention Planning in Goiás State Parks: A Business Intelligence Tool
> **Support for Wildfire Prevention Planning in Goiás State Parks Based on Hotspots**

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Cerrado](https://img.shields.io/badge/Biome-Cerrado-green?style=for-the-badge)
![CBMGO](https://img.shields.io/badge/Domain-Wildfire%20Management-red?style=for-the-badge)

---

## 📌 About the Project

This project presents an interactive **Business Intelligence (BI)** dashboard designed to support strategic planning and preventive actions against wildfires in the state parks of Goiás, Brazil.  
Using historical georeferenced hotspot data from **2016 to 2025**, the tool helps decision-makers identify critical areas, analyze fire recurrence patterns, and optimize the allocation of operational resources for environmental protection.

---

## 🚀 Live Interactive Dashboard

Explore the interactive Power BI dashboard directly in your browser:  
👉 **[Access the Power BI Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiNWRkNDQwN2QtOGRjOS00NjMwLTkzNTctMTBkMDZmZjY2YzhlIiwidCI6Ijk1NDYxM2ZhLWUzN2UtNDZkNi04NGYxLTJmYjNmMzY3MjExMyJ9)**

---

## 📊 Dashboard Preview

Here is a preview of the interactive analytical views structured in the Power BI dashboard:

<p align="center">
  <img src="assets/dashboard-1.png" alt="Dashboard Overview - Monthly Hotspots & Parks Ranking" width="100%">
</p>
<p align="center">
  <em>Figure 1: Hotspots temporal distribution by month and ranking by state park.</em>
</p>

<!-- You can add additional screenshots below following the same format -->
<!--
<p align="center">
  <img src="assets/dashboard-2.png" alt="Interactive Map View" width="100%">
</p>
<p align="center">
  <em>Figure 2: Geospatial distribution of hotspots across Goiás State Parks.</em>
</p>
-->

---

## 🔍 Key Findings & Ecological Insights

* **The Core Question:** How long does it take for a burned area in the Cerrado biome to burn again?
* **Statistical Discoveries:**
  * **Historical Average (Hotspot Recurrence Interval - IRFC):** ~3.05 years.
  * **Statistical Mode (Peak Frequency):** 2 years (representing 25.9% of all reburn events).
* **The Ecological Factor:** The Cerrado biome features a high density of grasses and herbaceous vegetation (fine fuels) with rapid biomass reconstitution capacity, explaining why the vast majority of reburns (87.2%) occur within a 4-year window.
* **Critical Units:** The **Terra Ronca State Park (PETER)** alone concentrated **50.7%** of the records (1,406 foci), followed by the **Serra Dourada State Park (PESD)** with **20.6%**.

---

## 📁 Data Sources & Methodology

The data pipeline relies entirely on trusted open-source environmental monitoring and geographic data:
* **Hotspot Data:** Acquired from the *BDQueimadas Program* provided by the National Institute for Space Research (INPE), utilizing the Suomi-NPP satellite (VIIRS sensor, 375m resolution).
* **Protected Areas:** State park boundaries obtained from the State System of Environmental Geoinformation (SIGA).
* **Analytical Approach:** Spatial joining and calculation of recurrence intervals (IRFC) to indirectly infer biomass accumulation patterns, climate correlations (Pearson's $r$), and potential fire severity.

---

## 🛠️ Technologies & Tools

* **Power BI / DAX:** Interactive dashboard development, measure creation, and data modeling.
* **QGIS:** Spatial processing, vector intersection of state park boundaries, and georeferencing.
* **Google Sheets / Statistics:** Initial data cleaning, descriptive statistics, and correlation analysis.

---

## 📁 Repository Structure

```text
wildfire-planning-goias/
│
├── README.md                          # Main project documentation (English)
├── powerbi/                           # BI visualization files
│   └── painel_focos_calor_goias.pbix  # Analytical dashboard in Power BI
└── assets/                            # Dashboard screenshots and preview images
    └── dashboard-1.png
