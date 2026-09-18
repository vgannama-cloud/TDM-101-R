# Project 5: Flight and Ice Cream Ratings, Grouped Aggregation and Binning

**Course:** TDM 101

## Overview
Applied `tapply`-based grouped aggregation and value binning across three datasets: 2006/1997 flight records and an ice cream ratings dataset. Computed average flight times by route, categorized ratings into descriptive tiers, and bucketed flight times into parts of the day.

## Techniques
- Grouped aggregation (`tapply`) across one and two grouping variables
- Value binning with `cut()` (ice cream rating tiers, time-of-day buckets)
- Frequency tables and sorting to find top-N categories
- Heatmaps of aggregated values across two dimensions (day of week x month)

## Key Finding
Identified the 20 busiest flight destination airports and the most common time-of-day window for departures/arrivals in 1997, and visualized total flight air time by day of week and month as a heatmap.

## Data
- `2006.csv`, `1997.csv` (flights): not included, large multi-hundred-MB files, sourced from the ASA Data Expo 2009 flights dataset
- `products.csv` (ice cream ratings): small, safe to include in `data/`
