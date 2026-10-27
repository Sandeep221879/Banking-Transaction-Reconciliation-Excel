# Banking Transaction Reconciliation & Operations Quality Analysis

## Project Overview

An Excel-based banking operations analytics project designed to reconcile source transactions against processed transaction records, identify operational discrepancies, measure SLA compliance, and analyze transaction processing efficiency.

The project includes an interactive dashboard that enables analysis across banking channels, branches, and transaction dates.

## Tools & Technologies

- Microsoft Excel
- Power Query / Excel formulas and lookup functions
- PivotTables and PivotCharts
- Slicers and Timeline
- VBA for workbook refresh automation
- ChatGPT for AI-assisted Excel development and troubleshooting

## Dataset Overview

- **Source Transactions:** 4,200
- **Processed Transaction Records:** 4,156
- **Unique Processed Transactions:** 4,108
- **Banking Channels:** ATM, CARD, IMPS, NEFT, UPI
- **Branches:** Bengaluru, Hyderabad, Mumbai, Pune

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Source Transactions | 4,200 |
| Unique Processed Transactions | 4,108 |
| Missing Transactions | 92 |
| Additional Duplicate Records | 48 |
| Amount Mismatches | 84 |
| Status Mismatches | 56 |
| SLA Compliance | 72.13% |
| SLA Breaches | 1,145 |
| Total Absolute Amount Difference | ₹1,06,314.96 |

## Dashboard Features

The interactive Excel dashboard includes:

1. Transaction volume analysis by banking channel.
2. SLA breach analysis by channel.
3. Missing transaction analysis by channel.
4. Average processing time analysis by channel.
5. Branch, Channel, and Transaction Date filters.
6. KPI summary cards for operational performance monitoring.

## Reconciliation Methodology

Transactions were matched using transaction IDs to identify missing and duplicate records. Source and processed amounts and statuses were compared to detect discrepancies.

Turnaround time was calculated using transaction and processing dates. Transactions processed within two days were classified as meeting the SLA, while transactions exceeding two days were marked as SLA breaches.

## Key Insights

- UPI accounts for the largest transaction volume.
- Hyderabad has the highest transaction volume among the four branches.
- 92 source transactions were identified as missing from processed records.
- 84 transactions contained amount mismatches.
- Overall SLA compliance was approximately 72%.
- Average processing time varies by banking channel.

## Business Recommendations

- Prioritize investigation of missing and duplicate transactions.
- Introduce additional validation checks for amount and status mismatches.
- Monitor SLA breaches by channel and branch to identify processing bottlenecks.
- Use processing-time trends to improve workload allocation and operational efficiency.

## AI-Assisted Development

ChatGPT was used as a support tool for formula troubleshooting, PivotTable configuration, dashboard connectivity, and Excel problem-solving.

The project was developed and tested in Microsoft Excel, including verification of interactive dashboard filters.

## Project File

**Excel_final_project1(3).xlsm**

Download the macro-enabled workbook and open it in Microsoft Excel desktop to explore the dashboard. Enable macros only after reviewing and trusting the workbook.

## Project Purpose

This project demonstrates practical Excel data analysis, banking operations reconciliation, data quality monitoring, KPI reporting, and interactive dashboard development.
