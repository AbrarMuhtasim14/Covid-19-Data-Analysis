# COVID-19 Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** `covid_19_data.csv` – Global COVID-19 cases as of **April 29, 2020**

---

## Project Overview
This project performs **exploratory data analysis (EDA)** on a global COVID-19 dataset using **Pandas**. The dataset includes daily records of confirmed cases, deaths, and recoveries across countries and regions up to **April 29, 2020**.

---

## Dataset Columns
| Column       | Description |
|--------------|-----------|
| `Date`       | Date of record (MM/DD/YYYY) |
| `State`      | State/Province (NaN for countries) |
| `Region`     | Country or region |
| `Confirmed`  | Total confirmed cases |
| `Deaths`     | Total deaths |
| `Recovered`  | Total recovered cases |

---

## Key Analysis Performed
- Loaded and inspected the COVID-19 dataset
- Sorted countries by **highest recovered cases**
- Identified **top 50 regions** with maximum recoveries
- Explored data structure for countries vs. sub-regions (e.g., US states, Chinese provinces)

> **Top 5 Countries by Recovered Cases (April 29, 2020):**
> 1. **Spain** – 132,929  
> 2. **Germany** – 120,720  
> 3. **US (National)** – 120,400  
> 4. **Italy** – 73,791  
> 5. **France** – 63,616

---

## Tools & Libraries
```python
pandas
