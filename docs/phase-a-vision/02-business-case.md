# Phase A – 02 Business Scenario & Drivers

## Business Drivers
The GreenOps Platform addresses three core drivers for modern enterprises:
- **Sustainability Mandate**: EU CSRD requires Scope 2/3 emissions reporting by 2026 — current GCP workloads lack automated carbon tracking.
- **Cost Pressure**: Cloud spend is 40%+ of IT budgets, but rightsizing and carbon-aware scheduling can deliver 30–40% savings.
- **Regulatory Compliance**: ESRS E1/E5 demands verifiable ESG data — manual reporting is error-prone and non-scalable.

## Primary Business Scenario
**Scenario**: "Carbon-Aware FinOps Transformation"

**Context**: A mid-sized European retailer with €50M annual GCP spend has 80% of workloads running on high-carbon regions (e.g., us-central1). Manual tagging and scheduling takes 20 engineer-days/month, with no automated reporting for CSRD audits.

**Actors**:
- Sustainability Director (Elena Voss): Needs automated emissions dashboards for board reporting.
- Cloud Ops Manager (Marcus Lind): Requires zero-touch workload migration to low-carbon regions.
- CIO (Sophia Patel): Demands ROI proof via TCO analysis.

**Process Flow**:
1. **Discovery**: Scan GCP resources for carbon intensity and cost inefficiencies.
2. **Optimization**: Auto-schedule workloads to green regions (e.g., europe-west3 during low-carbon hours).
3. **Execution**: Rightsize instances and generate CSRD-compliant reports.
4. **Monitor**: Real-time dashboards with FinOps + GreenOps metrics.

**Expected Outcomes**:
- 35% emissions reduction (Scope 2).
- 42% cost savings (€21M/year).
- Zero manual reporting effort.

## Value Stream Map
*(Edit [business-scenario.drawio](../diagrams/business-scenario.drawio) in diagrams.net for the full flow)*

| Value Stream Stage | Key Activities | Metrics | Owner |
|--------------------|---------------|---------|-------|
| Demand             | CSRD audit request | Report turnaround time | Elena Voss |
| Design             | Workload carbon profile | Optimization score | Marcus Lind |
| Build              | Auto-scheduling rules | Migration success rate | Sophia Patel |
| Operate            | Real-time monitoring | Emissions/cost delta | Operations Team |

**Status**: Scenario validated with stakeholders — approved 8 Dec 2025
