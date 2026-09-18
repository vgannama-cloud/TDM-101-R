# Project 11: Housing and Flight Delays, Advanced ggplot2 and Plot Design

**Course:** TDM 101

## Overview
Deeper `ggplot2` work combining Zillow housing data (across US census regions) and 1997 flight delay data, using custom functions to generate repeatable plots per airport, multiple `patchwork` layout arrangements, and a "good plot vs bad plot" comparison illustrating data visualization design principles.

## Techniques
- Boxplots and scatter plots grouped by region/category
- Custom functions to generate a summary and matching plot per input (per-airport delay analysis)
- `patchwork` layouts: grid, vertical stack, and custom asymmetric arrangements
- Deliberate "good vs bad" plot pairs to illustrate chart design pitfalls (misleading pie charts, chartjunk, poor color choices)

## Key Finding
Built a reusable function pipeline to summarize and plot arrival/departure delay trends by month for four different airports, then paired well-designed and poorly-designed versions of the same chart to demonstrate concrete data visualization best practices.

## Data
- `State_time_series.csv`, `Metro_time_series.csv` (Zillow), `1997.csv` (flights): check file sizes, likely too large to include, note source instead
