# Project 9: US Death Records, Merging, Cleaning and Distribution Analysis

**Course:** TDM 101

## Overview
Exploratory analysis of a US death records dataset, joining coded fields (race, marital status, day of week) against their decoder tables, cleaning sentinel/placeholder values, and visualizing age distributions across demographic groups.

## Techniques
- Merging a dataset with lookup/decoder tables (`merge`)
- Removing sentinel placeholder values (age recorded as 999)
- Boxplots of a numeric variable grouped by category
- Writing a reusable function to generate a plot for any given input value
- Grouped bar charts across two categorical dimensions (day of week, month)

## Key Finding
After cleaning out placeholder age values, compared age distributions between married and widowed individuals at specific ages, and visualized how marital status breakdowns shift across different days of the week and months.

## Data
- `DeathRecords.csv` and decoder tables (`Race.csv`, `MaritalStatus.csv`, `DayOfWeekOfDeath.csv`): check file sizes before including, the main records file may be large
