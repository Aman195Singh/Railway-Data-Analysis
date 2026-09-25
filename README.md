# Railway Data Analysis

Exploratory Data Analysis of railway train data using Python, Pandas,
Matplotlib, and Seaborn.

## Project Overview

This project analyzes railway train data to understand train distribution,
source-station activity, operating-day patterns, and journey categories.

## Objectives

- Identify the busiest source stations
- Analyze train distribution across operating days
- Compare weekday and weekend train activity
- Analyze trains operating from specific stations
- Categorize journeys
- Perform exploratory data analysis and visualization

## Dataset

The project uses `Railway_info.csv`.

### Important Columns

- Train_No
- Train_Name
- Source_Station_Name
- Destination_Station_Name
- days

## Data Cleaning

The following transformations were performed:

- Standardized source station names
- Standardized destination station names
- Standardized train names
- Standardized operating-day values
- Created `Day_Category`
- Created `Journey_Type`

## Analysis Performed

### Basic Analysis

- Total trains
- Unique train numbers
- Unique source stations
- Unique destination stations
- Operating days
- Missing-value analysis

### Station Analysis

- Top source stations
- Top destination stations
- Top 10 busiest source stations
- Average trains per day by source station

### Day Analysis

- Train distribution by day
- Weekday vs weekend distribution
- Saturday train analysis

### Journey Analysis

- Local/Shuttle
- Long-distance

## Visualizations

### Train Distribution by Day

![Train Distribution](outputs/train_distribution_by_day.png)

### Top 10 Busiest Source Stations

![Busiest Stations](outputs/busiest_source_stations.png)

### Weekday vs Weekend

![Weekday vs Weekend](outputs/weekday_vs_weekend.png)

## Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Learning

This project demonstrates practical skills in:

- Data cleaning
- Exploratory Data Analysis
- Filtering
- GroupBy
- Aggregation
- Feature creation
- Data visualization
- Analytical storytelling
