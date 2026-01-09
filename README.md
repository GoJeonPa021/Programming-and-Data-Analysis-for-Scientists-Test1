# Programming-and-Data-Analysis-for-Scientists-Test1
# Population and Education Data Analysis

This repository contains population and education datasets along with a Jupyter
notebook used for exploratory data analysis.

The main dataset is derived from **The State of World Population 2021 (SWOP)**,
published by the **United Nations Population Fund (UNFPA)**. The data track
demographic and education indicators relevant to the **ICPD Programme of Action**
and the **Sustainable Development Goals (SDGs)**.

---

## Files Included

- `SWOP-Data-2021.db`  
  SQLite database containing SWOP 2021 tables:
  - `demographic`
  - `education`
  - `region`

- `README_SWOP-Data-2021.txt`  
  Official documentation describing data sources, methodology, and variable
  definitions.

- `Country_Population_1960_2020.csv`  
  Historical country-level population data from 1960 to 2020.

- `icecream.csv`  
  Example dataset used for basic data handling and visualisation exercises.

- `Test_1.ipynb`  
  Jupyter notebook containing data loading, exploration, and analysis code.

---

## Data Description

### SWOP 2021 Database
The SWOP dataset includes:
- Population size and age distribution
- Fertility rates
- Life expectancy (male and female)
- Education enrolment rates and gender parity indices

Data are compiled using internationally standardised methodologies to ensure
cross-country comparability.

---

## How to Run

1. Open the notebook:
   ```bash
   jupyter notebook Test_1.ipynb
