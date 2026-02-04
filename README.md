# Product Engagement & Stickiness Analytics (Google Sheets)

Tools: Google Sheets (FILTER, UNIQUE, SORT, VLOOKUP, XLOOKUP), time-based analysis, KPI dashboards

## Goal
Analyze user activity trends after a new purchasing feature launch and evaluate product stickiness using DAU, WAU, MAU and stickiness ratios (DAU/MAU, WAU/MAU).

## What I did
- Filtered purchase events from the raw dataset using FILTER
- Created helper date fields (date, week_start, month_start)
- Built DAU / WAU / MAU calculations using UNIQUE, SORT and distinct user counts
- Connected tables with VLOOKUP / XLOOKUP
- Calculated stickiness: DAU/MAU and WAU/MAU
- Built time-series charts for DAU, WAU, MAU and stickiness trends

## Deliverables
- Spreadsheet model: **Product Metrics Analysis Project.xlsx**
- Trend charts (DAU/WAU/MAU) and stickiness dashboard (see dashboards)

## Repository structure
- `/dashboards` – charts
- `Product Metrics Analysis Project.xlsx` – full spreadsheet model
