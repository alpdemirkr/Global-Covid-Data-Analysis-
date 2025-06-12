# COVID-19 SQL Analysis Project

This project explores global COVID-19 trends using SQL queries on datasets containing case counts, deaths, population, and vaccination data. It was created to demonstrate advanced SQL analytics, window functions, joins, CTEs, and temporal insights.

## Data Sources

- `CovidDeaths`: Contains total cases, new cases, deaths, and population by location and date
- `CovidVaccinations`: Contains vaccination counts and dates by location

## Key Analyses

- Total cases and deaths over time
- Infection and mortality rates by population
- Rolling averages and growth rates
- Vaccination trends vs. case reductions
- Country and continent-level aggregations
- Anomaly detection in case spikes

## echniques Used

- Window functions: `LAG()`, `ROW_NUMBER()`, `ROLLING SUM`
- CTEs for layered queries
- Temporary tables and views
- Joins on date and location
