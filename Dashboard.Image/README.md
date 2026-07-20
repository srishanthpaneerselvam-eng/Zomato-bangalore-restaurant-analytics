# Zomato Bangalore Restaurant Analytics Dashboard

An end-to-end Power BI project that turns the raw Zomato Bangalore Restaurants dataset into an interactive analytics dashboard, covering data cleaning, DAX measures, and business insights.

## Overview

Bangalore has thousands of restaurants listed on Zomato, but the raw data is messy — inconsistent text, wrong data types, duplicate entries. This project cleans that data and builds a dashboard that surfaces the numbers a restaurant business or analyst would actually care about: ratings, cost, cuisine trends, and the impact of features like online ordering and table booking.

## Dataset

- *Source:* [Zomato Bangalore Restaurants (Kaggle)](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
- ~7,000 restaurants after cleaning
- 92 locations across Bangalore
- 15M+ total votes, 2K+ cuisine combinations

## Tools Used

- *Power BI Desktop* — dashboard design and modeling
- *Power Query (M)* — data cleaning and transformation
- *DAX* — KPI and measure calculations

## Data Cleaning Process

1. Applied Text.Clean and Text.Trim to strip hidden characters from text columns
2. Fixed data types across all columns (rate, votes, and cost converted from text to numbers)
3. Verified column quality — confirmed 0% errors and 0% empty values
4. Standardized rest_type and cuisines fields for consistent grouping
5. Identified and handled duplicate restaurant entries
6. Flagged and cleaned up encoding issues in restaurant names

## Dashboard

The report has two pages:

### 1. Market Overview
KPI cards (total restaurants, average rating, average cost), online order vs. table booking availability, top 10 locations by restaurant count, and top 10 cuisines.

![Market Overview](screenshots/market-overview.png)

### 2. Business Insights
Best-rated restaurant types, top 10 locations by average rating, most-voted restaurants, and a written insight summary.

![Business Insights](screenshots/business-insights.png)

Both pages include slicers for location, cuisine, rating, online order, and table booking — so anyone viewing the report can filter and explore on their own.

## Key Insights

- Only *15.2%* of restaurants offer table booking, but they rate *4.14★* on average vs. *3.62★* for those that don't
- *65.3%* of restaurants offer online ordering
- *North Indian* is the most listed cuisine, appearing in 2,148 restaurants
- *BTM* has the highest restaurant density of any locality (3.9K listings)
- *Pub, Cafe* is the top-rated restaurant type combination, averaging *4.7★*
- *Lavelle Road* is the highest-rated location in the city, at *4.14★* average

## Video Walkthrough

[Add your video link here]

## Files in This Repo

| File | Description |
|---|---|
| zomato-dashboard.pbix | Power BI file with full data model and report |
| screenshots/ | Dashboard page screenshots |
| Zomato_Bangalore_Dashboard_Report.pptx | Project summary presentation |

## Author

Srishanth P
Computer science and engineering.
