# Phase A – 01 Stakeholder Map & Management

## Stakeholder Register

| Stakeholder                  | Role / Title                     | Power | Interest | Attitude     | Key Concerns                              | Requirements / Expectations                                 |
|------------------------------|----------------------------------|-------|----------|--------------|-------------------------------------------|-------------------------------------------------------------|
| Elena Voss                   | Chief Sustainability Officer     | High  | High     | Supporter    | EU CSRD compliance, Scope 2/3 reduction  | Automated ESG reports, carbon dashboards, audit trail       |
| Sophia Patel                 | Chief Information Officer (CIO)  | High  | Medium   | Supporter    | ROI, risk, scalability                    | Clear business case, TCO analysis, 3-year roadmap           |
| Marcus Lind                  | Cloud Operations Manager         | Medium| High     | Neutral      | Operational stability, cost control       | Zero-downtime automation, GCP-native integration           |
| Raj Mehta                    | Finance Controller               | High  | Low      | Monitor      | Budget adherence, cost predictability     | Monthly savings reports, FinOps alignment                   |
| Compliance & Legal Team     | Regulatory Affairs               | Medium| High     | Blocker risk | Auditability, data residency              | Immutable logs, EU data sovereignty proof                   |
| Google Cloud Account Team    | Strategic Partner                | Low   | Medium   | Supporter    | Adoption of Carbon Sense tools            | Early access to carbon-region APIs                          |

## Power / Interest Grid

```mermaid
quadrantChart
    title Power / Interest Grid
    x-axis Low Interest --> High Interest
    y-axis Low Power --> High Power
    quadrant-1 Manage Closely
    quadrant-2 Keep Satisfied
    quadrant-3 Keep Informed
    quadrant-4 Minimal Effort
    "Elena Voss": [0.85, 0.90]
    "Sophia Patel": [0.65, 0.85]
    "Marcus Lind": [0.80, 0.55]
    "Raj Mehta": [0.25, 0.80]
    "Compliance Team": [0.75, 0.50]
    "Google Cloud Team": [0.45, 0.20]
