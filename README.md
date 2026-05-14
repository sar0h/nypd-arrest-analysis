# NYPD Arrest Analysis (January 2025) - Group 10

This is our final project for CIS 2300. We analyzed NYPD arrest data from January 2025 to look for patterns across NYC boroughs, age groups, and arrest trends.

## Team Members
- Sarah Sellami
- Valerie Grinberg
- Isaac Timmer
- Karla Jimenez

## What We Did

### Getting the Data
We used the Socrata API to pull around 24,000 rows from the NYC Open Data portal. The dataset was filtered to only include arrests from January 2025.

### Cleaning the Data
We cleaned the dataset using pandas by:
- renaming columns
- fixing date formats
- removing missing values
- creating simpler categories for analysis

### Analysis
The notebook includes:
- arrests by borough
- arrests by gender
- arrests by age group
- arrests by day of week
- age group vs borough comparisons
- violent vs non-violent offense analysis

### Charts
We used matplotlib to create bar charts, pie charts, and comparison graphs to visualize trends in the dataset.

## Tools Used
- Python
- pandas
- matplotlib
- sodapy
- python-dotenv

## Dataset
NYC Open Data:
https://data.cityofnewyork.us/
