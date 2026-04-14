# Python Data Analysis Capstone Project

## Understanding Socioeconomic Inequality Across Kenya's 47 Counties

A Data-Driven Analysis of Population, Poverty, and Development Across Kenya's 47 Counties

### Problem Statement
Kenya is a country of sharp contrasts — some counties are densely populated urban centers with high standards of living, while others are vast, sparsely populated regions struggling with poverty. This project brings together census and development data to analyze and visualize patterns, answering one core question: where in Kenya are people thriving, and where are they struggling — and why?

### Objectives
- Merge multiple county-level datasets into a single clean DataFrame using Pandas
- Perform statistical analysis using NumPy to identify patterns, correlations, and outliers
- Investigate relationships between population, poverty, inequality, and human development
- Build clear, informative visualizations using Matplotlib and Seaborn
- Map key findings geographically using GeoPandas

### Datasets
All datasets are publicly available CSV files from the Humanitarian Data Exchange (HDX) at https://data.humdata.org:

1. **Kenya 2019 Census** — Population by county, gender distribution, and population density
2. **GINI Coefficient per County** — Income inequality index for each of the 47 counties
3. **County Poverty Rates** — Poverty headcount estimates per county
4. **Human Development Index (HDI) per County** — Combined measure of health, education, and income per county
5. **Kenya Counties GeoJSON** — Geographic boundary coordinates for mapping all 47 counties

### Tools & Libraries
- **NumPy** — Statistical computations, array operations, ratios, averages
- **Pandas** — Data loading, cleaning, merging multiple datasets, groupby, sorting, filtering
- **Matplotlib** — Bar charts, histograms, scatter plots, subplots, custom formatting
- **Seaborn** — Heatmaps, correlation matrices, styled distribution plots
- **GeoPandas** — Choropleth maps showing county-level metrics on a map of Kenya

### Key Questions
1. Which are the top 10 most and least populated counties, and what are their population densities?
2. How does the male-to-female ratio vary across counties?
3. Which counties have the highest and lowest income inequality (GINI coefficient)?
4. Which counties have the highest poverty rates?
5. Is there a correlation between population density and poverty?
6. Is there a correlation between income inequality (GINI) and human development (HDI)?
7. Which counties rank high on HDI but still have high poverty — and what might explain that?
8. What does the geographic distribution of poverty and development look like on a map of Kenya?

### Project Structure
1. Data Collection & Loading
2. Data Cleaning & Merging
3. Exploratory Data Analysis
4. Statistical Analysis
5. Visualization
6. Geographic Mapping
7. Insights & Conclusion
