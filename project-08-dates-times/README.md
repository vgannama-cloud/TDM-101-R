# Project 8: Dates and Times, Restaurant Orders and Flight Schedules

**Course:** TDM 101

## Overview
Working with date/time data using `lubridate`: extracting day of week and month components from a restaurant orders dataset, and reconstructing full timestamps from a flights dataset to compare flight distance trends across major airports.

## Techniques
- Date parsing and component extraction (`lubridate::wday`, `month`, `year`, `ymd`, `make_datetime`)
- Grouped aggregation across time components (`tapply`)
- Multi-series line plots comparing trends across categories (four origin airports)

## Key Finding
Reconstructed full flight departure timestamps from separate date/time columns, then compared average and total flight distance by month across four major origin airports (Boston, Phoenix, Chicago, Seattle).

## Data
- `orders.csv` (restaurant): safe to include if small
- `1997.csv` (flights): not included, large, from the ASA Data Expo 2009 dataset
