# Feeding Malaysia: Local Crops and Food Imports

**Created by:** Akriti Bontha Venkata Surya  
**Course:** FIT3179 — Data Visualisation 2  
**University:** Monash University Malaysia  
**Student ID** 33157088
**Data Sources:** [data.gov.my](https://data.gov.my) | [World Bank Open Data](https://data.worldbank.org)

---

## Overview

**Feeding Malaysia: Local Crops and Food Imports** is an interactive data visualisation dashboard designed to explore Malaysia’s agricultural production and food import dependency trends.  
It provides insights into the nation’s local crop productivity, import reliance, and agricultural diversification across states and years.

The project combines multiple real-world datasets to present a clear narrative on Malaysia’s food security and self-sustainability between **2000–2022**.

---

## Objectives

- Visualise total crop production across Malaysian states.
- Compare annual crop yields and planted areas to identify efficiency.
- Track Malaysia’s dependence on food imports over time.
- Analyse crop distribution and share of total production by category.
- Present agricultural and economic patterns clearly and interactively.

---

## Visualisations Included

### Total Crop Production by State (2017–2022)
A choropleth map showing total crop production across Malaysia’s 13 states and 3 federal territories.  
The map highlights high-output regions such as Johor and Sarawak.

### Malaysia’s Food Import Dependency (2000–2021)
A line chart displaying Malaysia’s growing reliance on imported food items across two decades.

### Crop Composition by State (2022)
A stacked bar chart illustrating each state’s crop composition (paddy, fruits, vegetables, industrial crops, etc.) in 2022.

### Crop Efficiency: Planted Area vs Production
A scatter plot comparing each crop’s planted area against production output to reveal efficiency levels.

### Production Trends for Major Crops (2017–2022)
A multi-line chart visualising yearly production changes for major crops like paddy, fruits, and vegetables.

### Crop Share of Total Production (2022)
A horizontal bar chart ranking crop types by their percentage contribution to Malaysia’s total agricultural output.

### Malaysia’s Total Crop Production Over Time (2017–2022)
An area chart showing the nation’s total crop production growth trend and fluctuations.

---

## Data Sources
`total_production.csv` [Department of Agriculture Malaysia – data.gov.my](https://data.gov.my) - Total crop production (tonnes) by state (2017–2022). 
`crops_state.csv`  [data.gov.my](https://data.gov.my) - Detailed crop yield and planted area by crop type and state. 
`my.json` Custom GeoJSON (Malaysia map) - Used for state-level mapping in Vega-Lite choropleth. 
`import_data.csv` [World Bank Open Data](https://data.worldbank.org) - National food import dependency indicators (2000–2021). 

---

## 🛠️ Technologies Used

- HTML5 / CSS3 — Web layout and styling  
- JavaScript (ES6) — Data handling and embedding  
- Vega-Lite & Vega-Embed — Interactive data visualisations  
- GitHub Pages — Hosting and public access


