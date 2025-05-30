# MedDev
Title of Project: MedDev
Student Names: Sam Goldberg & Siem Yonas

## Thesis

This project aimed to explore the growth and global distribution of the medical equipment industry. Specifically, we examined how the field has evolved over time, analyzing where medical device manufacturers are located and how devices are imported and exported across different regions. Our objective was to visualize these trends and gain insight into the trajectory of the industry, including emerging markets, specialization shifts, and regulatory patterns.

## Tools and Technologies

We built an interactive dashboard using Dash (a Python framework combining Plotly, Flask, and React) to visualize the medical device ecosystem.

- **Plotly** was used for all visualizations due to its robust support for interactive, publication-quality graphs directly in Python.
- **Pandas** handled data wrangling and aggregation.
- **scikit-learn** was used for exploratory clustering and trend modeling.
- All visuals followed a consistent color scheme (Plotly Plasma) and were integrated into a unified dark-themed dashboard.

## Argument and Insights

We supported the following key conclusions with our dashboard:

- The medical device industry continues to grow globally and remains a viable sector for long-term careers.
- Surgical devices have consistently dominated the industry by volume.
- Offshore manufacturing of medical devices has accelerated over recent years.
- The emergence of novel devices correlates with increased representation in higher regulatory classes.
- A geographic shift is evident, with import activity rising in emerging markets.

## Final Visualizations and Interactivity

All visualizations were fully implemented and integrated into a working Dash application:

### 1. Stacked Area Chart
- Year vs. Device Count, broken down by the top 5 device types.
- Includes a time slider and toggle for linear vs. logarithmic scale.
- Tooltips display device count by year and type.

### 2. Bar Chart – Medical Specializations
- Top 5 medical specializations by device count.
- Bar color encodes number of unique device types.
- Interactive filters for year and geographic region.

### 3. Choropleth Map – Manufacturers
- Global map showing manufacturer count per country.
- Interactive tooltips with counts for manufacturers and devices.
- Filterable by year and region.

### 4. Bar Chart – Device Classes
- Distribution of devices by regulatory class (Class I, II, III).
- Stacked by device type.
- Includes interactive tooltips and legends.

### 5. Choropleth Map – Importers
- Geographic visualization of importer counts over time.
- Color intensity reflects number of importers per country.
- Tooltips show importer stats and changes across years.
