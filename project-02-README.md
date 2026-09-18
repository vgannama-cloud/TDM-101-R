# Project 2: Rotten Tomatoes Movie Ratings Analysis

**Course:** TDM 101

## Overview
Exploratory analysis of a Rotten Tomatoes movie dataset in R, looking at the distribution of movie ratings (G, PG, R, etc), the most prolific directors and studios, genre overlap patterns, and the relationship between MPAA rating and critical reception.

## Techniques
- Data cleaning (removing columns, fixing inconsistent rating labels)
- Frequency tables and cross-tabulation (`table`)
- Genre pattern matching (`grepl`, `grep`)
- Visualization: bar plot of rating distribution, mosaic plot of rating vs Tomatometer status

## Key Finding
Cross-tabulating MPAA rating against Tomatometer status (Fresh/Rotten/Certified Fresh) surfaced patterns in how a movie's rating relates to its critical reception, visualized with a mosaic plot.

## Data
- `rotten_tomatoes_movies.csv`: included in `data/`, a few MB
