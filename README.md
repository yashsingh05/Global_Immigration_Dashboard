# 🌍 Global Immigration & Demographics Analytics

## Overview
An end-to-end analytics project tracking global migration patterns, population shifts, and demographic trends across 217 countries using live data from the World Bank API — visualized in a 3-page interactive Power BI dashboard.

## Business Questions Answered
- Which countries are the top immigration destinations and emigration sources?
- How does GDP per capita correlate with migration and life expectancy?
- Which regions are gaining vs losing population through migration?
- How have migration patterns shifted from 2016 to 2023?

## Data Sources (Live APIs — No Kaggle)
| Source | Data Pulled |
|--------|------------|
| World Bank API | Population, Net Migration, GDP per Capita, Life Expectancy, Fertility Rate |
| World Bank Country API | Region, Income Level, Capital City |

## Key Findings
| Insight | Value |
|---------|-------|
| Countries analyzed | 217 |
| Years covered | 2016–2023 |
| Top immigration destination | United States (1.32M net migrants, 2023) |
| Top emigration source | Pakistan (1.62M net emigrants, 2023) |
| Most at-risk region | South Asia (-1.97M net migration, 2023) |
| GDP & Life Expectancy correlation | 0.62 (strong positive) |
| COVID-19 impact | Clear migration dip visible in 2020 across all regions |

## Dashboard Pages
| Page | Description |
|------|-------------|
| Page 1 — Global Overview | World map, KPI cards, top 10 countries, migration by region, trend line |
| Page 2 — Demographics Trends | GDP vs life expectancy scatter, fertility by region, population growth, GDP categories |
| Page 3 — Country Deep Dive | Drill-through page showing individual country profiles with migration trend, rate by year, and full statistics table |

## Advanced Dashboard Features
- 🗺️ Interactive world map with country-level data
- 🔍 Drill-through from any country → detailed country profile
- 🎨 Conditional formatting — green for immigration, red for emigration
- 🔘 3 slicers — filter by year, region, and income level
- 📈 Migration trend line showing COVID-19 impact in 2020

## Tools Used
- Python (Requests, Pandas, NumPy, Matplotlib, Seaborn)
- World Bank REST API
- Jupyter Notebook
- Power BI Desktop (3-page interactive dashboard)

## Files
- `immigration_analytics.ipynb` — Full Python pipeline with API calls
- `immigration_clean.csv` — Cleaned dataset with engineered features (1,953 rows, 15 columns)
- `Global_Immigration_Dashboard.pbix` — 3-page Power BI dashboard
- `immigration_viz.png` — Python visualizations
