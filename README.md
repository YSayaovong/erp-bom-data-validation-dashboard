# Manufacturing Operations ERP/BOM Analytics — Corrected README

## 1. Overview
This project analyzes engineering and manufacturing BOM errors, revision activity, rework cost, and error resolution time using a realistic operations dataset modeled in Excel.

Two dashboards are included:
- Engineering Error Analysis Dashboard  
- Revision Change Log Dashboard

---

## 2. Dashboard Preview
*(Already included in GitHub)*

---

## 3. How to Use the Dashboard

1. Open **Engineering_Analytics_Dashboard.xlsx**
2. Go to the **Dashboard** tab
3. Use slicers to filter by:
   - Error Type
   - Department
   - Month
4. Review primary KPIs:
   - Total Errors
   - Rework Cost
   - Avg Time to Resolve
   - Revision Count
5. Explore trend charts for deeper operational insights

---

## 4. Dataset Schema

### BOM_Error_Data
| Column | Description |
|--------|-------------|
| error_id | Unique error record |
| unit_id | Affected transformer/unit |
| error_type | Wrong part, wrong rev, routing issue, etc. |
| department | Eng, Mfg, Quality |
| date_logged | Date issue discovered |
| time_to_resolve_days | Days required to fix |
| cost_impact | Estimated rework cost |

### Revision_Change_Log
| Column | Description |
|--------|-------------|
| change_id | Revision event ID |
| part_number | Affected part |
| old_rev | Previous revision |
| new_rev | Updated revision |
| change_reason | ECO reason code |
| date_changed | Date of change |

---

## 5. Interview Talking Points

- Built a realistic simulation of ERP BOM operational analytics.
- Modeled KPI metrics used in manufacturing (rework cost, error frequency, resolution time).
- Designed dashboards mirroring real engineering/manufacturing workflows.
- Demonstrates Excel-based analytics exactly as used in most plants.

---

## 6. Tools Used
- Excel  
- Power Query  
- PivotTables  
- KPI dashboards  
- Mock operational datasets  

---
