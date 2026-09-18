# Project 10: Baby Names and Housing Trends, ggplot2 and dplyr

**Course:** TDM 101

## Overview
Introductory `ggplot2`/`dplyr` visualization work: comparing baby name popularity between 1997 and 2006 using Social Security Administration name data, then analyzing Zillow state-level housing data with scatter plots and time series.

## Techniques
- `dplyr` pipelines (`filter`, `group_by`, `summarise`, `arrange`)
- `ggplot2` bar charts, histograms, and faceted plots (`facet_wrap`)
- Custom fill-color mapping to highlight specific categories
- Combining multiple plots with `patchwork`
- Time series line plots grouped by region

## Key Finding
Compared the top 20 most popular baby names between 1997 and 2006 and how name popularity breaks down by first letter and sex, then tracked how median home listing prices trended over time across several US states.

## Data
- `yob1997.txt`, `yob2006.txt` (SSA baby names): small, safe to include in `data/`
- `State_time_series.csv` (Zillow): check file size before including, may be large
