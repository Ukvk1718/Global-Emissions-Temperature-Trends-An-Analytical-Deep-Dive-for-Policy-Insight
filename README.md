# 🌍 Global Emissions & Temperature Trends  
### *An Analytical Deep Dive for Policy Insight*

---

## 📌 Overview

This project investigates the historical trends and relationships between global emissions, temperature anomalies, and environmental policies. Utilizing robust datasets, Python analytics, and Power BI dashboards, we offer actionable insights to inform environmental policy and ESG strategies.

---

## ❓ Problem Statement

**How have global emissions and surface temperatures changed over time? What are the key drivers and anomalies, and how can this understanding guide data-driven environmental policies?**

---

## 📚 Background

With the increasing global shift toward ESG compliance and climate responsibility, understanding the historical interplay between emission levels, GDP, and temperature trends is crucial. This project aims to bridge the gap between raw climate data and policy decision-making by leveraging data science and business intelligence.

---

## 📊 Project Structure

### 🔍 Phase 1: Research & Data Collection

Collected from credible sources including OWID, NOAA, UNEP, and others:
- Annual CO₂, GHG, CH₄, and N₂O emissions by country
- Temperature anomaly datasets (global & hemispheric)
- Country-level GDP, population, HDI
- Historical global environmental policies (1750–2025)

---

### 🧼 Phase 2: Data Cleaning & Exploratory Analysis

Tool: `Python` (Pandas, Seaborn, Matplotlib)

Key Tasks:
- Data normalization, null-value handling, data type corrections
- Merged and enriched datasets
- EDA visualizations for:
  - Emissions by gas and country
  - Per capita emission disparity
  - Correlation between emissions and GDP
  - Temporal trends and anomalies

---

### 📈 Phase 3: Visualization & Reporting in Power BI

Tool: `Power BI Desktop`

#### Report Includes:

#### 🌐 **Global Emissions Overview**
- 🔹 **Key KPIs**: Highlights the highest-emitting countries (e.g., USA, China), total GHG, CO₂, Methane, and N₂O emissions.
- 📆 **Time Slicer**: Year and decade slicers allow users to interactively explore emissions data across historical periods from the 1750s to 2020s.
- 📊 **Trends Over Time**: Line chart showing long-term trends in emissions by gas type.
- 🌍 **Regional Breakdown**: Pie chart visualizing the contribution of each continent (Asia, Europe, North America, etc.) to total GHG emissions.
- 🔟 **Top 10 Countries**: Bar plot showcasing top national emitters along with per capita metrics.

#### 📈 **Emissions Trend & Correlation**
- 📈 **Year-over-Year Analysis**:
  - Average global YoY growth in total GHG emissions.
  - YoY change in GHG per capita.
- 🌍 **Region-wise YoY Growth**: Bar chart showing which regions are accelerating or reducing emissions over time.
- 📉 **GDP vs Emissions Correlation**:
  - Scatter plot comparing national GDP and GHG emissions with region color coding.
  - Offers insight into economic development vs climate cost.
- 🧪 **Python Visuals**:
  - Correlation matrix heatmap showing relationships between GDP per capita and emissions per capita.

#### 🌎 **Region & Country Breakdown**
- 🔍 **Drill-through Feature**:
  - From the region-wise pie chart on Page 1, users can click through to view country-specific details.
- 📌 **Country-level Insights**:
  - Per capita and total Ghg emissions.
  - Countries are categorized by region to support comparative analysis within and across regions.

#### 🌡️ **Temperature & Policy Insights**
- 🌡️ **Global Temperature Anomaly**:
  - KPI card summarizing average anomaly since 2000.
  - Line chart plotting global temperature deviations from the pre-industrial average since 1850.
- 🔮 **Forecasting Option**:
  - Projected anomaly trajectory based on recent decades.
- 📅 **Policy Timeline Overview**:
  - Visualization of environmental policies enacted per decade and per region (North America, Europe, Asia, etc.).

---

## 🔍 Key Findings

- **USA** leads cumulative GHG emissions
- **Asia** has the fastest growing emissions post-1950
- **GHG per capita** is highest in smaller oil-rich nations (Qatar, UAE, Bahrain).
- **Emissions are growing disproportionately** in emerging economies.
- **Temperature anomalies** rose drastically post-Industrial Revolution.
- **Environmental policies** often lag behind significant climate changes.

---

## 📊 Tools & Technologies

- 🐍 Python (Pandas, Seaborn, Matplotlib)
- 📊 Power BI (data storytelling)
- 📁 Excel (data source formatting)
- 🧠 ChatGPT, Gemini, and Google (research and synthesis)

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Meta Data for Project Final (Unclean).xlsx` | Initial Data gathered using Research |
| `Python Analysis.ipynb` | Python script used for analysis |
| `Cleaned_Global_Environmental_Data.xlsx` | Clean Data extracted from Python to use in Power BI  |
| `Global Environmental Analysis.pdf` | Power BI Report |
| `Bibliography.pdf` | Acknowledgement of sources and resources  |


---

## 📬 Contact

I'm Uddhav Kokra, an 18-year-old aspiring data analyst passionate about using data for decision-making.

🧑‍💻 Connect with me on [LinkedIn](https://www.linkedin.com/in/uddhavkokra) | 🐙 [GitHub](https://github.com/Ukvk1718)
