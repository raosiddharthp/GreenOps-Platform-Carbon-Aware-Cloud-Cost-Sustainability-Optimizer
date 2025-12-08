# Phase C – Information Systems Architecture

**GreenOps Platform**  
Data & Application Architecture for Carbon-Aware FinOps

## Key Artifacts
→ [01 Data Architecture](./01-data-architecture.md) (complete)  
→ [02 Application Architecture](./02-application-architecture.md) (next)

## High-Level Data Domains
| Domain                  | Description                                      | Primary System       |
|-------------------------|--------------------------------------------------|----------------------|
| Carbon Intelligence     | Real-time carbon intensity per GCP region        | Carbon API + BigQuery|
| Workload Inventory      | All running resources + metadata                 | Cloud Asset Inventory|
| Cost & Usage            | Billing export + reservations                    | BigQuery Billing     |
| ESG Reporting           | CSRD/ESRS-compliant emissions data               | Reporting Engine     |
| Optimization History    | Every scheduling/right-sizing decision + outcome | Audit Log (Cloud Audit Logs) |

**Status**: Data model ratified by Architecture Board — 15 Dec 2025
