# Post-COVID Rent Trends Analysis

## Overview
This project analyzes U.S. county-level rent trends before and after the onset of COVID-19, using Zillow Observed Rent Index (ZORI) data. The goal is to analyze geographic and temporal patterns in housing costs and understand how rental markets shifted during and after the pandemic.

## Key Questions
- How did rent levels change across U.S. counties following COVID-19?
- Were changes uniform, or did trends differ by location?
- What longer-term patterns emerged in the post-COVID period?

## Data
- **Primary Source:** Zillow Observed Rent Index (ZORI)
- **Supplementary data:** U.S. government data accessed via public API
- **Granularity:** County-level
- **Time frame:** Pre- and post-COVID periods

## Methods
- Data collection via public APIs and CSV sources
- Data cleaning and wrangling using Python (pandas, numpy)
- Aggregation and comparison of rent trends over time
- Exploratory analysis and visualization of geographic patterns

## Results
The analysis shows clear variation in post-COVID rent trends across counties, with some regions experiencing sharp increases while others remained relatively stable. These patterns highlight the uneven impact of the pandemic on housing costs and regional rental markets.

## Files
- `post_covid_rent_analysis.ipynb` — Fully executed analysis notebook
- `post_covid_rent_analysis.html` — Rendered HTML report with visualizations
- `data/` — Raw data used in the analysis

## How to View
For a quick, read-only view of the results, open the HTML report.  
For full reproducibility, the notebook can be run locally using the provided data files.
