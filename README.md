# Kenya Counties Analysis

Capstone project for Python Data Analysis. Looking at population, poverty, and development across Kenya's 47 counties.

## Problem Statement
Kenya is a country of sharp contrasts — some counties are densely populated urban centers with high standards of living, while others are vast, sparsely populated regions struggling with poverty. This project brings together census and development data to analyze and visualize patterns, answering one core question: where in Kenya are people thriving, and where are they struggling — and why?

## Objectives
- Merge multiple county-level datasets into a single clean DataFrame using Pandas
- Perform statistical analysis using NumPy to identify patterns, correlations, and outliers
- Investigate relationships between population, poverty, inequality, and human development
- Build clear, informative visualizations using Matplotlib and Seaborn
- Map key findings geographically using GeoPandas

## Datasets
All from HDX (https://data.humdata.org):
- Kenya 2019 Census — population by county, gender distribution, and population density
- GINI Coefficient per County — income inequality index for each of the 47 counties
- County Poverty Rates — poverty headcount estimates per county
- Human Development Index (HDI) per County — combined measure of health, education, and income per county
- Kenya Counties GeoJSON — geographic boundary coordinates for mapping all 47 counties

## Tools and Libraries
- NumPy — statistical computations, array operations, ratios, averages
- Pandas — data loading, cleaning, merging multiple datasets, groupby, sorting, filtering
- Matplotlib — bar charts, histograms, scatter plots, subplots, custom formatting
- Seaborn — heatmaps, correlation matrices, styled distribution plots
- GeoPandas — choropleth maps showing county-level metrics on a map of Kenya

## Key Questions
1. Which are the top 10 most and least populated counties, and what are their population densities?
2. How does the male-to-female ratio vary across counties?
3. Which counties have the highest and lowest income inequality (GINI coefficient)?
4. Which counties have the highest poverty rates?
5. Is there a correlation between population density and poverty?
6. Is there a correlation between income inequality (GINI) and human development (HDI)?
7. Which counties rank high on HDI but still have high poverty — and what might explain that?
8. What does the geographic distribution of poverty and development look like on a map of Kenya?

## Project Structure
1. Data Collection and Loading
2. Data Cleaning and Merging
3. Exploratory Data Analysis
4. Statistical Analysis
5. Visualization
6. Geographic Mapping
7. Insights and Conclusion
