# Executive Summary – Waze User Churn Analysis

## Project Overview
As part of the Waze data analytics team, this project investigates factors associated with user churn using the provided `waze_dataset.csv`.

## Data Insights
- Total records: 2,000
- Missing labels: 700 (35% of data)
- Device split: 55% Android, 45% iPhone
- Churn rate: 18%

## Churned vs. Retained Users
- Churned users took more drives (8 vs. 5) but over fewer days (2 vs. 5)
- They drove longer distances and had more km per driving day
- No significant difference in churn rate between iPhone and Android users

## Recommendations
- Investigate high-intensity users (likely long-haul drivers)
- Collect additional data on driver profession and travel purpose
- Refine user segments before modeling churn prediction
