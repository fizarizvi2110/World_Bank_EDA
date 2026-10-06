# World Bank Development Indicators Analysis

## Overview
This project explores the relationship between GDP per capita, fertility rate, and life expectancy across countries using 2021 World Bank data. The goal is to visualize and interpret how economic development correlates with demographic and health outcomes globally.

## Dataset
- Source: World Bank (2021)
- Variables: GDP per capita (USD), fertility rate (births per woman), life expectancy (years), by country

## Methods
- **Correlation matrix**: quantified the strength and direction of relationships between all three indicators
- **Clustermap**: grouped countries by similarity across the three indicators, revealing clusters of high-income/low-fertility/high-life-expectancy countries versus the inverse
- **Scatterplot**: visualized GDP per capita (log scale) against fertility rate, with life expectancy encoded as a color gradient, to show all three relationships in a single plot

## Key Findings
- A clear inverse relationship exists between GDP per capita and fertility rate: higher-income countries consistently show lower fertility rates
- Higher-income countries also tend to have higher life expectancy, while lower-income countries show the opposite pattern
- The clustermap confirms these patterns form distinct groupings rather than a smooth continuum, with high-income countries clustering tightly together on all three measures

## Tools
Python, pandas, seaborn, matplotlib

## Files
- `World_Bank.ipynb` — full analysis notebook, including data loading, visualization, and interpretation
