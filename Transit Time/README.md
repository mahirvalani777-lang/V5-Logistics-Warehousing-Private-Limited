# V5 Logistics – Transit-Time Optimization: Bhiwandi–Kolhapur Mini-Hub Assessment

A consulting-style assessment of whether a proposed **Kolhapur mini-hub** could improve V5 Logistics and Warehousing's Bhiwandi-centred Maharashtra network, based on estimated road driving times.

This report was created and prepared by **Mahir Valani**. | **Route validation date:** 23 October 2026

## Objective
Screen selected origins and destinations to identify where a Kolhapur mini-hub looks promising and where Bhiwandi should remain the serving hub, and recommend a selective two-hub structure rather than replacing Bhiwandi.

## Method
1. Use the Bhiwandi-centred network as the baseline.
2. Compare Google Maps estimated driving times from Bhiwandi and Kolhapur for 3 primary origins (Goa, Bengaluru, Chennai) and 8 secondary destinations.
3. Time saved = Bhiwandi estimate − Kolhapur estimate; reduction % = time saved ÷ Bhiwandi estimate.
4. Aggregate by summing route estimates (unweighted), then test analyst-selected planning scenarios (30%, 35%, 40%).

## Headline results (map estimates, not verified shipment performance)
| Category | Baseline | Proposed | Saved | Reduction |
|---|---:|---:|---:|---:|
| Primary routes (3) | 52h 54m | 35h 54m | 17h 00m | 32.14% |
| Secondary destinations (8) | 60h 18m | 24h 45m | 35h 33m | 58.96% |
| Combined illustrative (11) | 113h 12m | 60h 39m | 52h 33m | 46.42% |

**Audit note:** the project brief gave the secondary and combined reductions as 63.32% and 48.20%. Re-adding the route rows shows the brief's baseline/proposed totals do not reconcile (time saved does). The corrected figures above are used throughout; see Appendix C of the report and the `Data_Notes` sheet.

## Limitations
- Results are Google Maps driving estimates, not actual transit time or end-to-end lead time.
- Aggregates are unweighted sums, not volume-weighted network results; primary and secondary legs are not one journey.
- Some secondary values are approximate; Chennai–Kolhapur time is provisional; Solapur is preliminary; Nanded is flagged for validation.
- 30%/35%/40% are analyst-selected scenarios, not observed outcomes.
- No shipment volumes, frequencies, handling times, on-time records or costs were available. No savings are claimed.

## Files
| File | Description |
|---|---|
| `V5_Transit_Time_Optimization_Report.docx` / `.pdf` | Full report |
| `V5_Transit_Time_Analysis.xlsx` | Formula-driven calculations (inputs blue, formulas black) |
| `charts/` | High-resolution PNG charts and network schematic |

## Tools
Python (matplotlib, openpyxl), docx (Node.js), LibreOffice for PDF rendering.
