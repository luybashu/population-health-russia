# Visualization of Russian Medical Statistics: Population Health Status

This repository contains data, scripts, and visualizations from the project **“Population Health in Russia”**, part of the [WebMedStat.ru](http://WebMedStat.ru) initiative developed with support from the **Yandex Workshop**.

---

## Project Overview

Currently, official data on the health status of the Russian population are published by the **Federal State Statistics Service (Rosstat)** in numerous tables and documents, often in inconsistent formats (Excel, PDF, or Word).  
Such fragmented presentation makes it difficult to analyze trends and compare indicators. This project transforms those scattered statistical tables into **interactive, comprehensible dashboards**.

Data visualization of public health statistics helps:
- Improve the accessibility of information for medical professionals, researchers, and policymakers  
- Support data-driven decisions in healthcare management  
- Promote transparency and public engagement in health data

---

## Goal

To transform disparate statistical tables from Rosstat into **clear, interactive visual dashboards** published on the [WebMedStat.ru](http://WebMedStat.ru) platform.

---

## Data Description

- **Source:** Federal State Statistics Service (Rosstat)  
- **Reports used:** *Healthcare in Russia* (2001–2023), covering the years **1991–2022**  
- **Format:** Original tables in mixed formats (Excel, PDF, DOC) were parsed and unified using Python (pandas)  
- **License:** Publicly available, free for commercial and non-commercial use  

---

## Data Processing Workflow

### 1. Parsing and Cleaning
- Parsed Rosstat tables (various formats, inconsistent headers)
- Unified structure and naming

### 2. 
- Converted to pandas DataFrames for analysis

---

## Key Findings

### Morbidity by Major Disease Classes
- **Highest morbidity:** respiratory, circulatory, and musculoskeletal diseases  
- **Children under 1 year:** respiratory diseases dominate, followed by perinatal conditions and nervous system disorders  
- **Children (0–14):** respiratory diseases by a large margin, then injuries, skin, infections, and digestive diseases  
- **Adolescents (15–17):** respiratory diseases, followed by injuries, digestive, skin, and eye diseases  

### Morbidity Dynamics (1995–2022)
- **Increase:** hypertension-related and endocrine/metabolic diseases (notably diabetes)  
- **Decrease:** peptic ulcer disease, infectious and parasitic diseases, pregnancy-related conditions  

### Temporary Disability (2012–2022)
- **Main causes (by cases):** respiratory diseases and childcare leave  
- **Main causes (by duration):** maternity leave, respiratory diseases, injuries, neoplasms  
- Average duration of disability:  
  - Maternity leave — ~140 days  
  - Other causes — ~20 days  
  - Childcare leave — ~10 days  

### Regional Morbidity
- Regional incidence rates per 1,000 people for newly diagnosed diseases  


---

## Repository Structure


---

## Tools and Technologies

- **Jupyter Notebook** 
- **Python** (`Pandas`, `Numpy`, `Matplotlib`, `Seaborn`)
- **Tableau Public** — interactive visualization dashboards

---

## Dashboards (Tableau Public)

1. **Morbidity by Disease Class and Group**  
2. **Dynamics of Morbidity Over Time**  
3. **Causes of Temporary Disability**  
4. **Regional Morbidity Patterns**

👉 Explore online: [Population Health in Russia (Tableau Public)](https://public.tableau.com/)

---

## License

This project uses publicly available data.  
You are free to use, modify, and share with attribution.

---

## Contact

**Author:** [Your Name]  
**Project:** [WebMedStat.ru](http://WebMedStat.ru)  
**Email:** your_email@example.com  
**GitHub:** [github.com/yourusername](https://github.com/yourusername)

---
