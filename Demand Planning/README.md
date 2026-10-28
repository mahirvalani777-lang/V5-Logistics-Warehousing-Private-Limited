# V5 Logistics – Daily Demand Planning & Vehicle Allocation Optimization for ATM Distribution

Internship project report and toolkit documenting how daily ATM transportation (primary, secondary and last-mile) is planned and coordinated at V5 Logistics and Warehousing, the challenges that cause delays, and a practical framework for improvement.

**Prepared by:** Mahir Valani

> Evidence standard: work performed, outcomes recalled by the intern and analyst recommendations are kept separate. The reported cycle-time improvement is a recollection and is **not independently verified**. Recommendations are **proposals, not implemented changes**. No historical data have been invented.

## Scope
- Three stages: primary (inbound to warehouse), secondary (warehouse to district vendor/distribution point), last-mile (delivery to bank/site).
- Daily workload of approximately **150+ consignments** across the team's operation (consignments only; not machines, vehicles or capacity).
- Daily cadence: **Tier 1 Meeting / Daily Huddle** and **S&OE** (Sales and Operations Execution).
- The Bhiwandi vs Kolhapur network comparison is a separate project and is not merged here.

## Key figures
| Item | Value | Status |
|---|---|---|
| Daily consignments | 150+ | Reported (team level) |
| Operational cycle | ≈10 days → ≈4–5 days | Reported; cycle boundaries undefined |
| Reduction | 50% (to 5 days) to 60% (to 4 days) | Calculated |
| Holding charges, capacity, utilisation, damage, cost | – | Not available; baseline to be established |

## Files
| File | Description |
|---|---|
| `V5_Daily_Demand_Planning_Vehicle_Allocation_Report.docx` / `.pdf` | Full 23-section report |
| `V5_Daily_Operations_KPI_Dashboard.xlsx` | KPI definitions, tracker templates, cycle-time sheet and dashboard |
| `V5_Daily_Operations_Process_Flows.png` | As-Is and proposed To-Be process flows side by side |
| `V5_Daily_Operations_KPI_Dashboard_Preview.png` | Dashboard template preview (placeholders only) |
| `charts/` | Individual figures (flows, fishbone, cycle-time, roadmap, risk matrix) |

## Using the workbook
1. Blue cells are inputs; grey cells are formulas. Row 5 of the consignment tracker is a hypothetical example to delete.
2. Define cycle start/end events in `Cycle_Time` first (defaults are provisional).
3. Enter real data in `Consignment_Tracker`, `Vehicle_Allocation`, `Vendor_Tracker`, `Site_Readiness` and `Exception_Register`.
4. `Dashboard` shows "Baseline to be established" until data exist. Enter only verified vehicle capacity, in one unit.

## Limitations
No company records, cycle definitions, holding-charge amounts, capacities, volumes, damage or cost data were available. No external benchmarks are used.

## Tools
Python (matplotlib, openpyxl), docx (Node.js), LibreOffice for PDF rendering.
