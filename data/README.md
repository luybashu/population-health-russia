# Data Folder

This folder contains the processed datasets used in the project.  
The data is publicly available and can be used in any commercial and non-commercial projects.

- **Sourse:** Parsed from the official website of the [Federal State Statistics Service (Rosstat)](https://rosstat.gov.ru/folder/210/document/13218)
- **Description:** Analytical reports by Rosstat titled *"Healthcare in Russia"* from 2001 to 2023 (cover 1991-2022 period). The data comes in various formats and is not always consistent with each other.
  - The data are provided in multiple formats and vary between years.  
  - Inconsistencies across editions were corrected to create unified, analysis-ready datasets.  
- [Parsed Raw Data](https://disk.yandex.ru/d/OsAbA6Bhm1S3jQ)

## Contents
- `disease_classes.csv` – processed dataset containing annual morbidity statistics by ICD-10 disease classes for different population groups, as well as annual counts and durations of temporary disability cases.
- `disease_classes_regions.csv` – processed dataset containing annual primary morbidity rates (per 1,000 people) across Russian regions by major disease classes.
