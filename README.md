# FARS Crash Fatalities Dashboard

## Welcome!

FARS is the authoritative U.S. record of every fatal traffic crash, but its unprocessed form is a confusing jumble of over
a dozen different SAS files. We want to present some of the most critical crash related prevalence and factor information in a visually appealing, easy-to-use dashboard.

## What's in the dashboard

- **Overview tab** — five summary value boxes (total fatalities, fatal crashes, national rate per 100k, highest-rate state, lowest-rate state) plus an interactive choropleth map and a state-comparison bar chart of contributing factors.
- **About the Data tab** — data source, sample size, collection method, study population, and time period.

## Data source

All values come from NHTSA's published State Traffic Data fact sheets. 

## Files

- `DashboardV3.Rmd` — the flexdashboard source (uses `runtime: shiny`)
- `fars_data.csv` — the cleaned state level dataset

## Impact

We want researchers and policy analysts to use this dashboard to identify trends and engage in comparative analysis of state level crash data. 
Hopefully, tools like this dashboard can assist in the formulation and evaluation of targeted interventions that reduce traffic fatalities.

## Author

Jacob Shtulman, Emory University Rollins School of Public Health
