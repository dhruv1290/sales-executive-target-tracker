# Sales Executive Target Tracker (Excel)

Macro-enabled Excel dashboard tracking 5-day sales by executive and region.
Shows **Total Sales**, **Target**, **Target Hit %**, and **Away From Target %** using PivotTables, Slicers, and a small VBA helper.


## Features
- Filter by **Region** and **Sales Executive** with slicers
- Daily inputs (**Day1–Day5**) roll up to **Total Sales**
- KPI columns: **Target**, **Target Hit %**, **Away From Target %**
- Simple VBA macro (`SlicerConnection`) to toggle slicer–pivot connections

## Files
- `sales-executive-target-tracker-5day-v1.xlsm` – main workbook  

## How to use
1. Download the `.xlsm`.
2. Open in Excel and click **Enable Content** (macros).
3. Use the slicers (and checkbox if present) to filter/toggle connections.
4. Add/modify data in the table (headers: *Emp Code, Sales Executive, Region, Day1–Day5, Total Sales, Target, Target Hit %, Away From Target %*).
5. **Refresh** PivotTables if you change data: *Data → Refresh All*.

## Requirements
- Microsoft Excel (desktop). Macros must be enabled.
