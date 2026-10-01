# hotel-booking-demand-analysis-excel
Hotel booking analysis using Excel, Power Query, PivotTables, PivotCharts, and interactive slicers to explore cancellations, booking trends, and customer patterns.

# Hotel Booking Demand Analysis

Excel-based analysis of hotel booking patterns, cancellations, seasonality,
and customer booking behavior using Power Query, PivotTables, PivotCharts,
and interactive slicers.

## Project Overview

This project analyzes 119,390 hotel booking records from July 2015 to
August 2017 to explore booking volume, cancellation behavior, seasonality,
and customer booking patterns.

The analysis was developed entirely in Microsoft Excel using Power Query
for data preparation and PivotTables, PivotCharts, and slicers for analysis
and interactive reporting.

## Business Questions

The analysis focuses on the following questions:

- What is the overall booking cancellation rate?
- How does cancellation behavior differ between City Hotel and Resort Hotel?
- Which market segments show higher cancellation rates?
- How does cancellation rate vary across lead-time groups?
- How does monthly booking volume change throughout the observation period?

## Dataset

- Total records: 119,390 booking records
- Observation period: July 2015 – August 2017
- Domain: Hotel bookings
- Unit of analysis: Booking record
The dataset does not contain a unique customer identifier, so booking
records should not be interpreted as unique customers.

## Tools & Skills

- Microsoft Excel
- Power Query
- Data Cleaning
- Data Quality Validation
- PivotTables
- PivotCharts
- Interactive Slicers
- KPI Development
- Exploratory Data Analysis
- Dashboard Design

## Data Preparation

The dataset was cleaned and transformed using Power Query.

Key preparation steps included:

- Auditing missing values and data-type errors
- Handling missing values in the `children` field
- Preserving raw data for traceability
- Creating `total_nights`
- Creating `total_guests`
- Creating `arrival_date` and `year_month`
- Creating `lead_time_group`
- Creating guest and booking quality flags
- Auditing zero-night and no-guest booking records
- Validating row counts after transformations

ADR was excluded from the final analysis scope to avoid using a field
whose interpretation and transformation were not sufficiently reliable
for this portfolio analysis.

