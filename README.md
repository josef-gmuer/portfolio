# Data Analytics Portfolio

**Technical Skills: R, Python, PowerBI, Excel, SQL**

# Education

Masters of Economics, University of St. Gallen (In Progress)

Bachelors of Economics and Management, University of Geneva, 2024

# Projects

## European Energy Dashboard

Europe's electricity system is increasingly interconnected, yet the trade-offs between energy security, decarbonization, and cross-border dependency remain poorly understood. Using ENTSO-E generation and flow data, I built an interactive Power BI dashboard to map these dynamics across the continent. The analysis reveals stark divergences in national energy mixes and exposes how geopolitical shocks reshape trade flows, most notably, Ukraine's rapid pivot away from Russian electricity imports after 2022. For policymakers and energy analysts, the findings underscore the urgency of expanding grid interconnection capacity and reducing reliance on single energy corridors.

![European Energy Dashboard](/dashboardpic.png)

**[Download PowerBI_project.pbix](PowerBIprojectupdated.pbix)**


## Swiss Economic Policy Analysis

Switzerland's reputation for monetary stability masks a complex policy history, from negative interest rates to the sudden abandonment of the EUR/CHF floor in 2015. To analyze these dynamics, I built a full data pipeline pulling GDP, inflation, unemployment, and exchange rate data from the SNB and Federal Statistical Office APIs, then visualized 25 years of indicators using interactive Plotly charts in python. The analysis shows that the SNB's unorthodox negative rate regime successfully suppressed franc appreciation but came with persistent deflationary pressure. Going forward, the data suggests Switzerland faces a delicate normalization path as global rates converge.

![Swiss Macro Overlook](/swiss_macro_dashboard_REAL.png)

View the Colab file here: [Swiss Macro](https://colab.research.google.com/drive/1DuignLemXO6gkJ6YAmvphgRN-iYCax_T?usp=sharing)


## Global Carbon Pricing & Emissions Tracker

Carbon pricing is widely seen as the most efficient tool for reducing emissions — but with 73 jurisdictions now running carbon taxes or trading systems, how effective are they in practice? Drawing on World Bank carbon pricing data and Climate Watch emissions records from 2015–2024, I built an Excel dashboard to compare pricing levels, policy types, and emissions trajectories across regions. The results are underwhelming: average carbon prices remain far below levels economists consider effective, and there is limited evidence of a strong price-emissions relationship at current levels. The dashboard points to Europe as a relative success story, while highlighting the gap that remains in Asia-Pacific and Latin America, regions where scaling up carbon pricing should be the priority.

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
