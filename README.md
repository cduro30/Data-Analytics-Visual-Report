# Data-Analytics-Visual-Report
# Mindanao Climate-Agriculture Data Analysis Report  
### Dataset Focus: Crop Yield Trends vs Climate Variability (2019–2025)


## Data Cleaning Protocol Log

- **Raw Input Issues:** The dataset initially contained inconsistent formatting across yield values, redundant rows per crop-province combination, and variability in environmental measurements.
- **AI Cleaning Instruction Used:** “Standardize numeric fields, ensure consistent units for yield (tons per hectare), validate rainfall and temperature anomaly values, and structure the dataset for time-series analysis grouped by province and crop type.”
- **Cleaning Actions Performed:**
  - Ensured numeric consistency across all yield values  
  - Standardized rainfall (mm) and temperature anomaly fields  
  - Verified no missing values in critical analysis variables  
  - Structured dataset for multi-level comparison (Province × Crop × Year)
- **Result:**
  The dataset is now fully structured and analysis-ready for visualization and trend extraction.

## Visualization 1: Crop Yield Trend Over Time
(Insert Line Chart Above)

**Key Insight:**
Crop yields (rice, corn, cacao) show moderate fluctuations across years, with noticeable declines during periods of higher temperature anomalies. This suggests climate sensitivity in agricultural productivity, especially in drought-affected provinces.


## Visualization 2: Average Yield by Province
(Insert Bar Chart Above)

**Key Insight:**
Provinces with higher rainfall variability and stronger temperature anomalies (e.g., Cotabato and Davao del Sur) show lower average crop yield stability compared to more climatically stable regions such as Bukidnon.

---

## Human Analytical Narrative (Policy Insight)

The analysis reveals a clear relationship between climate variability and agricultural productivity across Mindanao provinces. While overall crop production remains relatively stable in favorable regions such as Bukidnon, provinces exposed to higher temperature anomalies and irregular rainfall patterns demonstrate reduced yield performance and greater volatility.

This pattern highlights the increasing vulnerability of agriculture to climate change impacts, particularly in rain-fed farming systems. For policymakers, this underscores the urgent need to strengthen climate-resilient agricultural programs, including irrigation expansion, drought-resistant crop varieties, and localized climate monitoring systems.

Strategic investment in adaptive agricultural infrastructure will be essential to stabilize food production and protect rural livelihoods in climate-sensitive regions of Mindanao.

---

## Tools Used
- Python (Pandas for data cleaning)
- Matplotlib & Seaborn (Data Visualization)
- Google Colab (Analysis environment)
- GitHub (Report deployment and documentation)

---

## Note
This report was generated as part of an AI-assisted data analysis exercise focused on regional development and climate resilience in Mindanao. All insights are intended for academic and policy simulation purposes.
