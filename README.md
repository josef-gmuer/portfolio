# Data Analytics Portfolio

**Technical Skills: R, Python, PowerBI, Excel, SQL**

# Education

Masters of Economics, University of St. Gallen (In Progress)

Bachelors of Economics and Management, University of Geneva, 2024

# Projects

## European Energy Dashboard

This Power BI dashboard provides an overview of Europe's electricity generation and cross-border power flows. Using ENTSO-E data, it visualizes total generation by energy source, highlights nuclear power generation since 2019, and maps electricity trade flows between countries. Interactive visuals allow users to compare energy mixes, analyze generation volumes in GWh, and explore interconnected European electricity markets. Dedicated pages analyze Germany's energy flows, and the shift in Ukraine's electricity imports following the 2022 Russian invasion.

![European Energy Dashboard](/dashboardpic.png)

**[Download PowerBI_project.pbix](PowerBIprojectupdated.pbix)**


## Swiss Economic Policy Analysis

This Python project analyzes Swiss economic indicators using SNB and Federal Statistical Office data. I built interactive Plotly visualizations examining GDP, inflation, unemployment, and exchange rates (2000-2024), exploring monetary policy impacts. Demonstrates full data pipeline: API collection, cleaning, analysis, and visualization in Colab.

![Swiss Macro Overlook](/swiss_macro_dashboard_REAL.png)

View the Colab file here: [Swiss Macro](https://colab.research.google.com/drive/1DuignLemXO6gkJ6YAmvphgRN-iYCax_T?usp=sharing)


## Global Carbon Pricing & Emissions Tracker

This Excel dashboard analyzes carbon pricing mechanisms across 73 jurisdictions worldwide. Using World Bank State and Trends of Carbon Pricing (2024) and Climate Watch emissions data, I examined pricing trends from 2015-2024, compared carbon tax versus emissions trading systems, and explored the relationship between carbon prices and emissions. Built with Excel pivot tables, charts, and formulas.

![Carbon Pricing Dashboard](/excelupdate.png)

**[Download Carbon_Pricing_Dashboard.xlsx](Carbon_Pricing_Dashboardupdate.xlsx)**

### File Structure
- `Dashboard` — Interactive KPIs and regional breakdown table
- `Data_Pricing` — Raw carbon price observations
- `Data_Emissions` — Emissions time series 
- `Analysis` — Merged panel dataset with log-transformed variables
- `Econ_Analysis` — Descriptive statistics, price trends (2015–2023), and carbon tax vs. ETS comparison
- `Chart_PriceTrends` — Average price trends by policy type and region
- `Chart_Scatter` — Latest year price vs. emissions data by jurisdiction
- `Chart_Heatmap` — Jurisdiction-by-year price matrix for heatmap visualization
