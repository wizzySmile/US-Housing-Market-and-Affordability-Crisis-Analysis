# US Housing Market and Affordability Crisis Analysis Project

Welcome to the US Housing Market and Affordability Crisis Analysis Project repository!

This project analyzes the **housing affordability crisis in the United States (2018–2024)**.  
It combines **Python data processing/cleaning** and **API integration** with **Tableau visualization** to provide a clear picture of both **affordability outcomes** and **drivers**.


---
## Table of Contents
- [Project Overview](#-project-overview)
- [Tools Used](#tools-used)
- [Project Requirements](#project-requirements)
- [Project Goal](#project-goal)
- [BI: Analytics & Reporting](#bi-analytics--reporting)
- [Tableau Dashboard Overview](https://public.tableau.com/shared/2C7HTW59F?:display_count=n&:origin=viz_share_link)
- [Repository Structure](#-repository-structure)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [About](#about)
- [Contact](#contact)
---

## 📖 Project Overview

This Project involves:
**Data Collection**
   - CSV datasets downloaded from housing market and demographic sources (e.g., U.S. Bureau of Labor Statistics, Zillow, American Community Survey (ACS)).
   - API calls to retrieve updated housing estimate data.

**Data Cleaning/Report (Python)**
   - Handling missing values and inconsistent formats.
   - Normalizing state and regional identifiers.
   - Creating calculated fields (e.g., housing burden, affordability index).
   - Exporting clean datasets and creating a report for Tableau dashboard.

**Visualization (Tableau)**
   - **Affordability Outcomes (What’s happening):**
     - State affordability ranking.
     - Regional affordability map.
     - National affordability trend (housing burden).
   - **Affordability Drivers (Why it’s happening):**
     - Supply pressures (listings, months of supply).
     - Demand pressures (population growth, competition).
     - Income trends vs. home value growth.

---

## Tools Used
- Tableau
- Python

---

## Project Requirements

### Building the Housing Affordability Analytics Solution

#### Project Goal


The objective of this project is to design and implement an end-to-end analytics solution that transforms **historic housing, income, and demographic data (2018–2024)** into actionable insights.  
Specifically, the project aims to:

- Collect and consolidate **historic CSV datasets** and **API-sourced data** on housing supply, demand, income, and home values.  
- Use **Python scripts** to clean, normalize, and merge these datasets, ensuring consistency and analysis readiness.  
- Perform **exploratory data analysis (EDA)** in Python to validate data quality, understand distributions, and calculate affordability metrics such as housing burden and affordability index.  
- Develop **Tableau dashboards** to visualize:
  - **Affordability Outcomes (What’s happening)** → state rankings, regional maps, national affordability trends.  
  - **Affordability Drivers (Why it’s happening)** → supply shortages, demand pressures, income growth, and home value changes.  
- Provide stakeholders with a clear narrative of the **USA House Affordability Crisis**, showing both the outcomes and the drivers across time and regions.  
- Enable **data-driven understanding of historic trends**, supporting research, policy analysis, and strategic planning for future housing challenges.  

This integrated approach ensures that users can both monitor **historic affordability outcomes** and uncover the **structural forces** behind them, creating a comprehensive view of how the crisis unfolded.

#### Specifications
- **Data Sources**: Import historic housing, income, and demographic data (2018–2024) from CSV files and API endpoints.  
- **Data Quality**: Cleanse and normalize datasets using Python to resolve missing values, inconsistent formats, and ensure analysis readiness.  
- **Integration**: Merge multiple sources (housing supply, demand, income, home values) into a single structured dataset for Tableau.  
- **Scope**: Focus on historic data trends (2018–2024) to analyze affordability outcomes and drivers; real-time monitoring is not required.  
- **Documentation**: Provide clear documentation of the data cleaning process, data model, and dashboard structure to support analysts, researchers, and stakeholders.  
- **Visualization**: Build Tableau dashboards with two main sections:  
  - *Affordability Outcomes* → national trends, regional maps, state rankings.  
  - *Affordability Drivers* → supply shortages, demand pressures, income growth, home value changes.  
---

### BI: Analytics & Reporting

#### Advanced Analytics (Python)

#### Objective
Use Python to prepare and analyze historic housing, income, and demographic data (2018–2024), ensuring clean, reliable datasets for visualization.  

#### Key Tasks
- *Data Collection*: Import CSV datasets and retrieve API data.  
- *Data Cleaning*: Handle missing values, normalize formats, and merge sources.  
- *Exploratory Data Analysis (EDA)*: Validate data quality, distributions, and calculate affordability metrics (housing burden, affordability index).  
- *Feature Engineering*: Create calculated fields for supply pressures, demand pressures, income trends, and home value growth.  
- *Documentation*: Provide clear records of the cleaning and transformation process.  

Python ensures the data is structured and analysis-ready before moving into Tableau for visualization.

#### Tableau Dashboard

#### Objective
Develop Tableau dashboards to deliver detailed insights into housing affordability outcomes and drivers.  

📊 *Tableau Dashboard*  
- View the interactive Tableau dashboards here: [Tableau Dashboard Link](https://public.tableau.com/shared/2C7HTW59F?:display_count=n&:origin=viz_share_link)

#### Dashboard Sections
- **Affordability Outcomes (What’s happening)**  
  - State affordability ranking  
  - Regional affordability map  
  - National affordability trend (housing burden)  

- **Affordability Drivers (Why it’s happening)**  
  - Supply pressures (listings, months of supply)  
  - Demand pressures (population growth)  
  - Income vs. home value trends  

These dashboards provide stakeholders with a clear narrative of the **USA House Affordability Crisis**, empowering *data-driven policy and strategic decision-making*.

---


## 📂 Repository Structure

| Path | Description |
|------|-------------|
| `advance-analytics/` | Python-based advanced housing affordability analytics |
| `advance-analytics/us_housing_crisis_analytics.ipynb` | Jupyter notebook for historic affordability analysis (2018–2024) |
| `dataset/` | Source data used for the project |
| `dataset/raw-data/` | Raw housing, income, and demographic datasets (CSV + API) |
| `dataset/raw-data/census_income.csv` | Raw census income data |
| `dataset/raw-data/cpi_data.csv` | Raw consumer price index data |
| `dataset/raw-data/mortgage-rates.csv` | Raw mortgage rates data |
| `dataset/raw-data/population-2018-2024.csv` | Raw population growth data |
| `dataset/raw-data/zillow-home-value.csv` | Raw Zillow home value data |
| `dataset/raw-data/zillow-inventory.csv` | Raw Zillow inventory data |
| `dataset/raw-data/zillow-rental-price.csv` | Raw Zillow rental price data |
| `dataset/raw-data/zillow-sales-count.csv` | Raw Zillow sales count data |
| `dataset/raw-data/household-estimate-2018-2024_API/` | API-sourced household estimate data |
| `dataset/cleaned-data/` | Cleaned and structured datasets ready for Tableau |
| `dataset/cleaned-data/census_income_2018_2024.csv` | Cleaned census income data |
| `dataset/cleaned-data/cpi_2018_2024.csv` | Cleaned CPI data |
| `dataset/cleaned-data/home_value_2018_2024.csv` | Cleaned home value data |
| `dataset/cleaned-data/inventory_2018_2024.csv` | Cleaned inventory data |
| `dataset/cleaned-data/mortgage_2018_2024.csv` | Cleaned mortgage data |
| `dataset/cleaned-data/pop_growth_2018_2024.csv` | Cleaned population growth data |
| `dataset/cleaned-data/rental_price_2018_2024.csv` | Cleaned rental price data |
| `dataset/cleaned-data/sales_count_2018_2024.csv` | Cleaned sales count data |
| `dataset/cleaned-data/household_estimate_2018_2024.csv` | Cleaned household estimate data |
| `scripts/` | Python scripts for data cleaning and reporting |
| `scripts/data-cleaning/` | Jupyter notebooks for cleaning raw housing affordability data |
| `scripts/data-cleaning/data-cleaning-us-house-affordability.ipynb` | Notebook for cleaning and preparing datasets |
| `scripts/report/` | Reporting scripts and outputs |
| `scripts/report/report-python-script/` | Jupyter notebook for generating affordability reports |
| `scripts/report/report-python-script/report-us-house-affordability.ipynb` | Notebook for report generation |
| `scripts/report/us_housing_affordability_report.csv` | Generated affordability report (CSV) |
| `docs/` | Project documentation and visualizations |
| `docs/python-charts/` | Visualizations generated from Python analysis |
| `docs/python-charts/active-listings-trend(top 5 states).png` | Active listings trend (top 5 states) |
| `docs/python-charts/correlation-matrix-affordability-drivers.png` | Correlation matrix of affordability drivers |
| `docs/python-charts/median-home-value-trend.png` | Median home value trend |
| `docs/python-charts/median-income-trend.png` | Median income trend |
| `docs/python-charts/mortgage-bruden-trend.png` | Mortgage burden trend |
| `docs/python-charts/mortgage-burden-trends(top 5 states).png` | Mortgage burden trends (top 5 states) |
| `docs/python-charts/price-to-income-ratio-trend.png` | Price-to-income ratio trend |
| `docs/python-charts/price-to-income-trend(top 5 states).png` | Price-to-income trend (top 5 states) |
| `docs/python-charts/price-to-income-trend.png` | Price-to-income trend |
| `docs/python-charts/regional-affordability-index.png` | Regional affordability index |
| `docs/python-charts/regional-affordability-index-forecast.png` | Regional affordability index forecast |
| `docs/python-charts/rent-burden-trend.png` | Rent burden trend |
| `docs/python-charts/rent-burden-trend(top 5 states).png` | Rent burden trend (top 5 states) |
| `docs/python-charts/state-affordability-comparison.png` | State affordability comparison |
| `docs/python-charts/supply-trend.png` | Supply trend |
| `docs/python-charts/top-most-affordable-state.png` | Top most affordable state |
| `docs/python-charts/us-affordability-index-map.png` | US affordability index map |
| `docs/python-charts/us_housing_market_indicators.png` | US housing market indicators |
| `docs/tableau-dashboard/` | Tableau dashboard files and snapshots |
| `docs/tableau-dashboard/usa-house-market_affordability-crisis-dashboard.twbx` | Tableau packaged workbook file |
| `docs/tableau-dashboard/tableau-dashboard-snapshot/` | Tableau dashboard snapshot images |
| `docs/tableau-dashboard/tableau-dashboard-snapshot/usa-house-affordability-crisis-dashboard-snapshot.png` | Snapshot of the Tableau dashboard |
| `README.md` | Main project overview and documentation |

---

## Key Insights

- Housing affordability **worsened nationally between 2018–2024** as home values and rental prices rose faster than household incomes.  
- **Supply shortages** (low inventory, fewer active listings) combined with strong demand pressures (population growth, household formation) created upward pressure on housing costs.  
- The **housing burden** (share of income spent on housing) reached historic highs, with some regions facing disproportionate affordability challenges compared to the national average.  
- **Mortgage rate increases** cooled demand but did not ease affordability, as limited supply and high prices kept the burden elevated.  
- Regional analysis shows that **high-growth states** experienced sharper affordability crises, while a small group of states remained relatively more affordable.  
- By 2024, modest recovery in supply and stabilizing prices suggest early signs of balance, but affordability remains a critical challenge for households nationwide.

---

## Recommendations

- Prioritize **supply-side interventions** such as expanding housing inventory, incentivizing new construction, and reducing regulatory barriers to ease affordability pressures.  
- Implement **targeted affordability programs** for regions and states with the highest housing burden, ensuring support reaches households most at risk.  
- Strengthen **income growth policies** (wage support, job creation, tax relief) to help households keep pace with rising housing costs.  
- Monitor and address **mortgage rate impacts**, balancing demand cooling with affordability support for first-time buyers.  
- Encourage **regional planning and zoning reforms** to align housing supply with population growth and household formation trends.  
- Use **data-driven dashboards and analytics** to continuously track affordability outcomes and drivers, guiding smarter policy and investment decisions.  

---

## Limitations

- The analysis is based on **historic data (2018–2024)** and does not account for real-time market fluctuations or policy changes beyond this period.  
- Data sources are limited to **housing, income, demographic, and mortgage datasets**; factors such as local zoning laws, tax policies, and government subsidies were not included.  
- Affordability metrics (housing burden, affordability index) rely on **aggregate averages**, which may mask variations at household or community levels.  
- Regional comparisons are constrained by **data availability and granularity**; some local markets may not be fully represented.  
- The project focuses on **national and state-level trends**, meaning micro-level affordability challenges (e.g., city or neighborhood dynamics) are outside the scope.  

---

## About
Hello! I'm Wisdom Chinemere Mpamugo, also known as Wisdom Analytics.  
As a Data Analyst, I help organizations make data-driven decisions by building scalable data solutions and translating data into actionable insights.

--

## Contact
Let's stay in touch! Feel free to connect with me on this platform:
- LinkedIn: [https://www.linkedin.com/in/wisdom-mpamugo-98b5151b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app]
  
- Twitter: [https://x.com/WisdomAnalyst01]
