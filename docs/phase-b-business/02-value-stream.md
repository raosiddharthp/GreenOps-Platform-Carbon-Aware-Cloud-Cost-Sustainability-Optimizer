# Phase B – 02 Value Streams

## Value Stream 1: Carbon-Aware Optimization

| Stage              | Trigger                            | Key Activities                                   | Actor / System         | Output / Metric                         |
|--------------------|------------------------------------|--------------------------------------------------|------------------------|-----------------------------------------|
| 1. Demand          | New workload or schedule change    | Detect workload + current carbon intensity       | Cloud Asset Inventory  | Workload profile created                |
| 2. Analyze         | Profile received                   | Score regions by carbon + cost                   | GreenOps AI Engine     | Top 3 low-carbon regions identified     |
| 3. Plan            | Scores available                   | Generate migration/scheduling plan               | Scheduler Service      | Optimized execution plan                |
| 4. Execute         | Plan approved (auto)               | Live-migrate or schedule in green region/time    | Compute Engine APIs    | Workload running in green region        |
| 5. Verify          | Post-execution                     | Measure actual carbon & cost reduction           | Monitoring Dashboard   | 35% avg emissions drop, 42% cost saving |

**Lead time**: < 5 minutes (fully automated  
**Value**: €20M+ annual savings + 1,500 tCO₂e reduction

## Value Stream 2: CSRD-Compliant ESG Reporting

| Stage              | Trigger                            | Key Activities                                   | Actor / System         | Output                                  |
|--------------------|------------------------------------|--------------------------------------------------|------------------------|-----------------------------------------|
| 1. Collect         | Month-end                          | Pull all GCP usage + carbon data                 | BigQuery + Carbon API  | Raw dataset                             |
| 2. Enrich          | Raw data available                 | Apply allocation rules, tagging, scope 2/3 calc  | Reporting Engine     | Enriched dataset                        |
| 3. Generate        | Dataset ready                     
