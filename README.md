# 🌍 Energy Data Pipeline for Emissions & Renewable Analysis

**Author:** Shanon Mwangi  

---

## 📌 Overview
This project builds an end-to-end data pipeline using Databricks and PySpark to analyse global energy consumption, CO₂ emissions, and renewable energy adoption.

The goal is to transform raw energy data into meaningful insights that highlight global trends, regional disparities, and the relationship between renewable energy and emissions.

---

## ⚙️ Tech Stack
- Databricks  
- PySpark  
- Delta Lake  
- Python  
- Plotly / Power BI  

---

## 🛠️ Pipeline Architecture

The pipeline follows a structured data engineering workflow:

1. **Data Ingestion**
   - Raw CSV dataset loaded into Databricks Unity Catalog

2. **Data Cleaning**
   - Removed duplicates (Country-Year level)
   - Replaced invalid zero values with NULLs

3. **Feature Engineering**
   - CO₂ emissions per capita  
   - Energy consumption per capita  
   - Renewable energy share  

4. **Data Storage**
   - Stored processed data using Delta Lake (ACID + scalable)

5. **Analytical Layer**
   - Filtered clean dataset for reliable analysis (post-2010)

---

## 📊 Key Visualisations

### 🌐 Global Renewable Energy Share (2024)
![Renewable Map](your-map-image.png)

---

### 📈 Regional CO₂ Emissions Trends
![Emissions Trend](your-trend-image.png)

---

### 🔍 Renewable Energy vs CO₂ Emissions
![Scatter Plot](your-scatter-image.png)

---

## 🔑 Key Insights

- **North America & Middle East** show the highest CO₂ emissions per capita  
- **Europe** demonstrates a steady decline in emissions, likely due to renewable adoption and policy  
- **Africa** has the lowest emissions, reflecting lower industrialisation  
- A **negative relationship** exists between renewable energy share and emissions  
- Renewable adoption varies significantly across regions due to infrastructure and policy differences  

---

## 🚀 Key Takeaways

- Renewable energy plays a critical role in reducing emissions  
- However, emissions are also influenced by:
  - industrial activity  
  - energy demand  
  - economic structure  

- Data engineering is essential for transforming raw data into actionable insights for energy decision-making  

---

## 📂 Project Structure
