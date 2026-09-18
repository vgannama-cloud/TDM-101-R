# Project 1: Flights and Olympics Frequency Analysis

**Course:** TDM 101

## Overview
Exploratory data analysis in R across three datasets: US airports, 2007 domestic flight records, and 120 years of Olympic athlete data. Goal was finding the busiest airports, most common flight origins, and cities that hosted the most Olympic events.

## Techniques
- Loading and subsetting data frames (`read.csv`, `data.table::fread`)
- Filtering by state (`subset`)
- Frequency tables (`table`, `sort`, `tail`)
- Dot chart visualizations (`dotchart`)

## Key Finding
Identified Indiana's airports within the national airport dataset, found the top 20 most common flight origin airports in 2007, and determined the 10 cities that have hosted the most Olympic Games appearances by athlete-city record count.

## Data
- `airports.csv`, `athlete_events.csv`: small, included in `data/`
- `2007.csv` (flights): not included, 600MB+. Sourced from the ASA Statistical Computing Data Expo 2009 dataset
