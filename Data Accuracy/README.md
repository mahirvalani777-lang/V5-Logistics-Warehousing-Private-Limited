# V5 Logistics – Daily Demand Planning and Vehicle Allocation Optimization (Shipment Data Accuracy)

Internship project report, tracking workbook and methodology note covering daily demand planning, vehicle allocation, shipment coordination and the shared Excel tracking dashboard used at V5 Logistics and Warehousing.

**Prepared by:** Mahir Valani

## Files
| File | Description |
|---|---|
| `V5_Daily_Demand_Planning_and_Vehicle_Allocation_Optimization_Report.docx` / `.pdf` | 19-section report |
| `V5_Daily_Operations_Tracking_Dashboard.xlsx` | Shipment tracker, dashboard, accuracy audit, KPI definitions |
| `V5_KPI_Dashboard_Visual.png` | KPI dashboard visual |
| `charts/` | Process flow, before/after process, accuracy chart, root-cause matrix, SIPOC, exception workflow, roadmap, cycle-time chart |

## Workbook structure
| Sheet | Purpose |
|---|---|
| Instructions | How to update records and maintain data quality |
| Lists | Dropdown values; status-update window (placeholder, edit to policy) |
| Shipment_Tracker | 500 rows; 24 input fields (blue) plus formulas (grey): missing-field count, completeness, on-time, overdue, update compliance |
| Dashboard | KPIs calculated from the tracker; "No data" until records are entered |
| Accuracy_Audit | Part A illustrative calculation; Part B estimate; Part C monthly workload; Part D real audit entry |
| KPI_Definitions | Formula, relevance, data source, frequency |
| Sample_Entries | Fictitious layout examples; not linked to calculations |

No pre-existing workbook was available, so this file was built from scratch from the recommended field structure. Adjust field names to match the team's actual tracker. Formulas were tested with temporary dummy data (completeness, accuracy, on-time, readiness, holding, damage and update compliance), which was then removed.

## KPI formulas
- **Shipment data accuracy** = accurate records ÷ records audited × 100. Accurate = complete (all mandatory fields) **and** verified correct against source order, vendor confirmation or delivery evidence.
- **Completeness** = records with all mandatory fields ÷ records reviewed × 100.
- **On-time delivery** = delivered by committed date ÷ due × 100. **Site readiness** = confirmed ready ÷ assessed × 100. **Holding-charge incidence** and **damage incidence** = flagged consignments ÷ delivered consignments × 100. **Status-update compliance** = updated within window ÷ requiring updates × 100. **Vehicle utilization** = actual utilised ÷ available capacity × 100 (needs verified capacity).

## Source of each number
| Number | Source | Status |
|---|---|---|
| 150+ daily consignments | Team operation, as reported | Reported (consignments, not machines or vehicles) |
| 150 × 26 = 3,900 per month | Calculation | Illustrative scale |
| ≈10% improvement in shipment data accuracy | Team experience | **Estimated relative improvement; no formal audit** |
| 1,000 records; 900 → 990; 90% → 99%; +9 points; 10% relative | Constructed example | **Illustrative calculation only; not an audit finding** |
| ≈10 days → ≈4–5 days; 50–60% reduction | Reported; calculation | Reported; cycle start/end undefined |

The ≈10% estimate (team experience) and the 90% → 99% example (illustrating the formula) are separate. A 10% relative improvement is not a 10-percentage-point increase.

## Limitations
No historical audit, holding-charge amounts, vehicle capacities, incident counts or damage rates are available, and no financial saving is claimed. The tracker is a practical shared record and does not replace an ERP.

## Tools
Python (matplotlib, openpyxl), docx (Node.js), LibreOffice for PDF.
