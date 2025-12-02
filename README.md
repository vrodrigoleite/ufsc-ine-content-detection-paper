# Time Series Analysis of Hospital Admissions in the Brazilian Unified Health System (SIH/SUS): Trends in Morbidity, Mortality, and Hospital Costs in Santa Catarina (2015–2024)

This project performs a comprehensive ten-year analysis of hospital admissions in the Brazilian Unified Health System (SIH/SUS), focusing on the state of Santa Catarina from 2015 to 2024. The goal is to explore long-term trends in hospital utilization, demographic patterns, clinical demand, mortality, and healthcare expenditures using administrative health data.

## 🔍 Objectives
- Consolidate and preprocess SIH/SUS hospitalization records from monthly DBC files.
- Build a reproducible ETL workflow using Python and PySUS.
- Compute key health indicators such as:
  - Monthly admissions  
  - Hospital mortality rate  
  - Average length of stay  
  - Mean and total hospitalization costs  
  - Distribution by ICD-10 chapters  
  - Trends by age group and gender
- Perform exploratory time-series analysis to identify structural trends and the impact of major events (e.g., COVID-19).
- Provide a foundation for future machine learning applications (clustering, forecasting, risk modeling).

## 🧠 Methodology
- **Extraction:** Automated download and conversion of DBC files via PySUS.  
- **Transformation:** Data cleaning, ICD-10 standardization, type correction, feature engineering, and construction of monthly aggregates.  
- **Load:** Consolidation of cleaned data into Parquet format for efficient analysis.  
- **Analysis:** Time-series exploration, demographic stratification, morbidity profiling, and financial trend evaluation.

## 📊 Key Findings
- Strong seasonal patterns and a sharp decline in hospitalizations during COVID-19, followed by rapid recovery.
- Higher hospitalization volume among women and older adults.
- ICD-10 chapter analysis reveals structural drivers such as obstetric care, chronic diseases, and respiratory conditions.
- Mortality and length of stay returned to pre-pandemic levels after 2022.
- Healthcare expenditures increased substantially during and after the pandemic.

## 🛠️ Technologies Used
- Python 3.11  
- Jupyter Notebook  
- PySUS  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Parquet/CSV data formats

## 📚 Academic Context
This repository supports the development of a scientific article analyzing long-term hospitalization trends using administrative health data. The methods and visualizations here form the basis for exploratory data analysis, health system monitoring, and future machine learning tasks.

---

Feel free to explore the notebooks, scripts, and figures included in this repository. Contributions and suggestions are welcome!
