# Cost Assessment

## V5 Logistics & Warehousing Private Limited

This report was created and prepared by **Mahir Valani**.

A scenario-based assessment of transportation costs for selected movements through the existing **Bhiwandi hub** and a proposed **Kolhapur mini-hub**. This assessment complements the [Transit Time analysis](../Transit%20Time/) and uses the same network context and hub allocation.

> The model uses supplied assumptions. It is not an independently verified record of company expenditure. All savings shown are **modelled gross transportation-cost savings**, not realised results.

## Objective

Estimate the illustrative transportation-cost difference between the two hub scenarios and assess how incremental Kolhapur hub costs affect the net benefit.

## Method

- Compare identical volumes in both scenarios: **80 machines per route** for Goa, Bengaluru and Chennai, using four loads of 20 machines in a 6-tyre vehicle.
- Calculate cost per machine as **primary cost per vehicle ÷ 20 + secondary cost + last-mile cost**.
- Calculate gross savings as **Bhiwandi cost − Kolhapur cost**, with the percentage reduction measured against Bhiwandi cost.
- Calculate net modelled benefit as **gross savings − incremental hub cost**. The hub-cost input is editable and illustrative; the break-even incremental hub cost equals gross savings.

## Modelled Results

| Route | Bhiwandi cost | Kolhapur cost | Gross savings | Reduction |
|---|---:|---:|---:|---:|
| Goa | ₹5,36,000 | ₹4,44,000 | ₹92,000 | 17.16% |
| Bengaluru | ₹5,92,000 | ₹5,05,840 | ₹86,160 | 14.55% |
| Chennai* | ₹6,34,400 | ₹5,52,000 | ₹82,400 | 12.99% |
| **Total** | **₹17,62,400** | **₹15,01,840** | **₹2,60,560** | **14.78%** |

\* Chennai primary costs are supplied working figures pending confirmation.

The **break-even incremental hub cost is ₹2,60,560**. A net benefit of 5–6% would imply hub costs of ₹1,72,440 to ₹1,54,816. These figures are reverse-calculated scenarios, not actual expenses.

**Audit note:** The brief's combined reduction of 14.79% recalculates to 14.784%, which rounds to **14.78%**. All rupee totals reconcile exactly.

## Limitations

- Volumes are modelling assumptions.
- Actual incremental hub costs are unavailable.
- Chennai inputs remain unconfirmed.
- Secondary savings are assumed at a flat ₹500 per machine.
- All machines are assumed to be bound for the Kolhapur catchment.
- Cost distances differ from those used in the Transit Time report.

## Project Files

| File | Description |
|---|---|
| [Transportation Cost Optimization Report](V5_Transportation_Cost_Optimization_Report.docx) | Full assessment report in Word format |
| [Transportation Cost Model](V5_Transportation_Cost_Model.xlsx) | Formula-driven Excel model; inputs use blue/yellow formatting and formulas use grey |

## Tools Used

Python (matplotlib, openpyxl), docx (Node.js), and LibreOffice for PDF rendering.
