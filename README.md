# Visualization of Russian Medical Statistics: Population Health Status

This repository contains data, scripts, and visualizations from the project **“Population Health in Russia”**, part of the [WebMedStat.ru](http://WebMedStat.ru) initiative developed with support from the **Yandex Workshop**.

## Project Overview

Currently, official data on the health status of the Russian population are published by the **Federal State Statistics Service (Rosstat)** in numerous tables and documents, often in inconsistent formats (Excel, PDF, or Word).  
Such fragmented presentation makes it difficult to analyze trends and compare indicators. This project transforms those scattered statistical tables into interactive, comprehensible dashboards.

Data visualization of public health statistics helps:
- Improve the accessibility of information for medical professionals, researchers, and policymakers  
- Support data-driven decisions in healthcare management  
- Promote transparency and public engagement in health data

**General Goal**  
Transform disparate statistical tables from Rosstat into **clear, interactive visual dashboards** published on the [WebMedStat.ru](http://WebMedStat.ru) platform.

**Specific Goal of this part of the project**
Visualise and investigate: 
• Morbidity by major disease classes and groups
• Trends and dynamics of morbidity over time
• Regional patterns of morbidity across Russia
• Causes of temporary disability

## Repository Structure
The project is organized into the following folders:
- **`data/`** – Raw and processed data files</summary>
- **`script/`** – Jupyter notebooks for data cleaning and exploration</summary>
- **`results/`** – Project deliverables</summary>

---

## Tools and Technologies

- **Jupyter Notebook** 
- **Python** (`Pandas`, `Numpy`, `Matplotlib`, `Seaborn`)
- **Tableau Public** — interactive visualization dashboards

## Data Processing Workflow

### 1. Parsing
- Parsed Rosstat tables (various formats, inconsistent headers) 
- Unified structure and naming

### 2. Data Load and Pre-processing 
- Converted to pandas DataFrames for analysis
- Combining data from different years and population groups into a single DataFrame
- Data cleaning (numbers in various formats, including symbols, spaces, non-breaking spaces, and decimal parts sometimes separated by a comma and sometimes by a period -> numerical form)
- Analysis and correction of outliers

### 3. EDA 

### 4. Dashboards

The interactive dashboard allows users to explore 30 years of rainfall and snowfall data in Navarcles by year and month.
👉 Explore online: [Population Health in Russia (Tableau Public)]([https://public.tableau.com/](https://public.tableau.com/app/profile/liubov.shubina/viz/Russian_Population_Health/health))
> Open `Russian_Population_Health.twbx` with **Tableau Desktop Public Edition (v2022.3+)**

Dashboard includes:
1. Morbidity by Disease Class and Group
2. Dynamics of Morbidity Over Time  
3. Causes of Temporary Disability 
4. Regional Morbidity Patterns
   
---

## License

This project uses publicly available data.  
You are free to use, modify, and share with attribution.

## Acknowledgments
Thanks to the WebMedStat.ru team, and especially **Andrey Ivanov**, for their dedication to this socially significant volunteer initiative.
Special recognition goes to **Olga Matushevich**, data analyst and team lead for this part of the project, for her guidance and mentorship.


