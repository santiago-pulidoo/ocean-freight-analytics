# Ocean Freight Performance Analysis
### USA to Brazil Corridor — 2024

## Overview
End-to-end data analysis case study examining the logistics performance of ocean freight exports from the United States to Brazil for a U.S.-based industrial machinery manufacturer. The analysis covers 3,531 shipment records across three routes and four carriers over a full calendar year.

## Business Questions
1. **Operational Performance:** What is the percentage of on-time vs delayed shipments, and which routes concentrate the highest non-compliance?
2. **Transit Time Analysis:** Are there significant differences between ETA and ATA by carrier that would justify a reassessment of the current carrier mix?
3. **Incident Analysis:** Do incidents correlate with specific carriers or seasons, enabling the anticipation of high operational risk periods?

## Key Findings
- **87.9% on-time rate** across all completed shipments (2-day tolerance window applied)
- Delays are evenly distributed across routes — no single route concentrates non-compliance
- All four carriers share a median delay of 1 day — no carrier stands out as significantly underperforming
- Incidents correlate more strongly with seasonality than with carriers — **April–May peak at 18.8–20.6%** incident rate; Q4 shows elevated port congestion

## Dataset
- **Source:** Synthetic dataset built on real operational knowledge of the USA–Brazil ocean freight corridor
- **Records:** 3,531 shipments (post-cleaning: 3,531 records, 28 columns)
- **Period:** January–December 2024
- **Routes:** Houston TX → Santos BR | Jacksonville FL → Santos BR | Port Everglades FL → Santos BR
- **Carriers:** Maersk, Hapag-Lloyd, MSC, CMA CGM

## Tools
| Tool | Purpose |
|---|---|
| Python (pandas) | Data cleaning & analysis |
| Google Colab | Development environment |
| Tableau Public | Dashboard & visualizations |
| GitHub | Version control & portfolio publishing |

## Methodology
Google Data Analytics six-phase framework: Ask → Prepare → Process → Analyze → Share → Act

## Dashboard
[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/OceanFreightPerformanceDashboard-USAtoBrazil2024/Dashboard1)

## Files
- `ocean_freight_analysis.ipynb` — Full analysis notebook (data cleaning, EDA, business questions)
- `container_shipments_2024_clean.csv` — Clean dataset used for analysis
