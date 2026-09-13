# Sales Executive Target Tracker (Excel)

Macro-enabled Excel dashboard tracking 5-day sales performance by executive and region.

## Dashboard Preview

![Sales Executive Target Tracker Dashboard](Dashboard_overview_target_tracker.png)

## Project Overview
This dashboard tracks daily sales performance for a team of sales executives across multiple regions (Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, Surat). It consolidates 5 days of raw sales entries per executive into key performance metrics, letting managers quickly see who's hitting targets and who isn't.

## My Process
- Structured raw daily sales data (Day1–Day5) by executive, region, and employee code
- Built calculated fields for Total Sales, Target Hit %, and Away From Target %
- Created PivotTables to summarize performance by executive and region
- Designed an interactive dashboard using slicers for region and executive filtering
- Wrote a VBA macro (`SlicerConnection`) to toggle slicer-to-pivot table connections dynamically

## Key Insights
- Jagdish Chandra and Rachita Anupam were the top performers on Total Sales
- Target Hit % varied significantly across the team, from ~58% to ~78%, highlighting uneven performance against targets
- Regional performance differences suggest some regions may need additional support to hit targets

## Features
- Filter by Region and Sales Executive with slicers
- Daily inputs (Day1–Day5) roll up automatically to Total Sales
- KPI columns: Target, Target Hit %, Away From Target %
- VBA macro to toggle slicer-pivot connections

## Files
- `Sales Executive Target Tracker.xlsm` – main workbook

## How to Use
1. Download the `.xlsm` file
2. Open in Excel and click **Enable Content** (macros)
3. Use the slicers to filter by Region or Sales Executive
4. Add/modify data in the table (headers: Emp Code, Sales Executive, Region, Day1–Day5, Total Sales, Target, Target Hit %, Away From Target %)
5. Refresh PivotTables if data changes: **Data → Refresh All**

## Tools & Skills Used
- Microsoft Excel — PivotTables, Slicers, Dashboard Design
- VBA (macro-driven slicer control)
- Data Aggregation & KPI Calculation
- Performance Analysis

## Requirements
Microsoft Excel (desktop). Macros must be enabled.
