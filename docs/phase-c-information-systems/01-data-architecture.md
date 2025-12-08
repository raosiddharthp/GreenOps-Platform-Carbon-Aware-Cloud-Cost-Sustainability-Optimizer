# Phase C – 01 Data Architecture

## Conceptual Data Model

| Entity                  | Key Attributes                                      | Source System               |
|-------------------------|-----------------------------------------------------|-----------------------------|
| GCP Project             | project_id, name, labels                            | Cloud Asset Inventory       |
| Compute Instance        | instance_id, zone, machine_type, tags               | Compute Engine API          |
| Carbon Intensity        | region, timestamp, grams_co2e_per_kwh               | Google Carbon API           |
| Billing Record          | sku, cost, usage_amount, credits                    | BigQuery Billing Export     |
| Optimization Event      | event_id, workload_id, from_region → to_region, savings_co2e, savings_usd | GreenOps Engine |
| ESG Report              | report_id, period, scope_2, scope_3, audit_hash     | Reporting Engine            |

## Data Flow Diagram (simplified)
