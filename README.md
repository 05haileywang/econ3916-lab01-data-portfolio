# econ3916-lab01-data-portfolio
# The Data Portfolio — Big Mac Index Analysis

## Objective
This project evaluates global currency valuation by applying purchasing power parity theory to The Economist's Big Mac Index, quantifying over- and under-valuation across 57 countries and more than two decades of data.

## Methodology
- Sourced the Big Mac Index dataset directly from The Economist's GitHub repository, spanning 57 countries and 45 time periods (2000-04 through 2026-07), including a 54-country cross-section for July 2024
- Computed implied purchasing power parity (PPP) exchange rates and derived valuation percentages relative to actual market exchange rates
- Classified the dataset's structural types — cross-sectional, time series, and panel — to inform appropriate analytical treatment
- Conducted a missing data diagnosis, identifying Russia's exclusion from the series as Missing Not At Random (MNAR) given its geopolitically driven removal
- Built visualizations, including a bar chart of currency valuations and a time series comparison, to communicate trends and outliers

## Key Findings
- The Swiss franc showed persistent overvaluation, reaching +41.8% in the July 2024 cross-section
- The Japanese yen was undervalued on average in every decade covered by the series, indicating a sustained rather than transient deviation from PPP
