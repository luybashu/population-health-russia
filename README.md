# Visualization of Russian Medical Statistics: Population Health Status

This repository contains data, scripts, and visualizations from the project **“Population Health in Russia”**, part of the [WebMedStat.ru](http://WebMedStat.ru) initiative developed with support from the **Yandex Workshop**.

## Project Overview

Currently, official data on the health status of the Russian population are published by the **Federal State Statistics Service (Rosstat)** in numerous tables and documents, often in inconsistent formats (Excel, PDF, or Word).  
Such fragmented presentation makes it difficult to analyze trends and compare indicators. This project transforms those scattered statistical tables into interactive, comprehensible dashboards.

Data visualization of public health statistics helps:
- Improve the accessibility of information for medical professionals, researchers, and policymakers  
- Support data-driven decisions in healthcare management  
- Promote transparency and public engagement in health data

This part focuses on the health status of the population, covering: 
• Morbidity by major disease classes and groups
• Trends and dynamics of morbidity over time
• Regional patterns of morbidity across Russia
• Causes of temporary disability

**Goal**
Transform disparate statistical tables from Rosstat into **clear, interactive visual dashboards** published on the [WebMedStat.ru](http://WebMedStat.ru) platform.

## Repository Structure
The project is organized into the following folders:
- **`data/`** – Raw and processed data files</summary>
- **`script/`** – Jupyter notebooks for data cleaning and exploration</summary>
- **`results/`** – Project deliverables</summary>

## Data Description

- **Source:** Federal State Statistics Service (Rosstat)  
- **Reports used:** *Healthcare in Russia* (2001–2023), covering the years **1991–2022**  
- **Format:** Original tables in mixed formats (Excel, PDF, DOC) were parsed and unified using Python (pandas)  

---

## Tools and Technologies

- **Jupyter Notebook** 
- **Python** (`Pandas`, `Numpy`, `Matplotlib`, `Seaborn`)
- **Tableau Public** — interactive visualization dashboards

## Data Processing Workflow

### 1. Parsing and Cleaning
- Parsed Rosstat tables (various formats, inconsistent headers)
- Unified structure and naming

### 2. 
- Converted to pandas DataFrames for analysis

---

## Dashboards

The interactive dashboard allows users to explore 30 years of rainfall and snowfall data in Navarcles by year and month.
👉 Explore online: [Population Health in Russia (Tableau Public)](https://public.tableau.com/)
> Open `Dashboard_Navarcles.twbx` with **Tableau Desktop Public Edition (v2022.3+)**

Dashboard includes:
1. Morbidity by Disease Class and Group
2. Dynamics of Morbidity Over Time  
3. Causes of Temporary Disability 
4. Regional Morbidity Patterns
   

---

## License

This project uses publicly available data.  
You are free to use, modify, and share with attribution.

---

## Acknowledgments


