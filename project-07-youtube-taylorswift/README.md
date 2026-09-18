# Project 7: YouTube Channels and Taylor Swift Discography, Custom Functions

**Course:** TDM 101

## Overview
Data cleaning and custom function writing applied to a top YouTube channels dataset and a Taylor Swift discography dataset: cleaning messy numeric strings, aggregating by category, and building reusable filter functions.

## Techniques
- String cleaning of numeric columns stored as text (`gsub`, `as.numeric`)
- Grouped aggregation (`tapply`) across one and two dimensions
- Writing reusable custom functions (filter by threshold, filter by album name, find top row by group)
- Basic bar and line plots

## Key Finding
Built reusable functions to filter a discography by audio "energy" threshold or by album name, and identified the top YouTuber by subscriber count within the Gaming and Music categories.

## Data
- `most_subscribed_youtube_channels.csv`, `taylor_swift_discography_updated.csv`: small, safe to include in `data/`
