# Project Summary

## Objective

Analyse a large developer survey dataset to understand respondent characteristics, technology usage, technology preferences, and compensation-related patterns.

## Work completed

### Data exploration
The exploration notebook loads the survey dataset, inspects the first records, checks the dataset dimensions, examines column data types, calculates age statistics, and counts unique countries.

### Data wrangling
The wrangling notebook covers duplicate detection and removal, missing-value investigation, treatment of missing values, and compensation normalisation. Compensation is converted to an annual basis for weekly, monthly, and yearly records.

### Exploratory data analysis
The EDA notebook examines age and compensation, calculates medians, uses an IQR-based approach to inspect compensation outliers, and explores correlations between age and selected work/compensation variables.

### Data visualisation and SQL
The visualisation notebook demonstrates SQLite connections, SQL queries, grouping, table inspection, and multiple visualisation techniques including histograms, box plots, scatter plots, bubble plots, pie charts, and comparison charts.

### Web scraping
The web-scraping notebook extracts programming-language and average annual salary information from a provided web page and writes the resulting table to `popular-languages.csv`.

### IBM Cognos dashboard
The supplied dashboard screenshots present current technology usage, future technology trends, and demographics.
