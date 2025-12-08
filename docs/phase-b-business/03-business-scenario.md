# Phase B – 03 Business Scenarios

## Scenario 1: "Carbon-Aware Black Friday"

**Context**  
European retailer expects 10× traffic spike on Black Friday. Current setup runs everything in us-central1 (high carbon).

**GreenOps Response**  
- 48h before event: AI engine predicts load and pre-warms instances in europe-west8 (currently 92% renewable).  
- During peak: Workloads automatically shift to lowest-carbon regions in real time.  
- Post-event: Auto-downscale + generate CSRD-compliant emissions spike report.

**Outcome**  
- Peak carbon intensity reduced 68% vs previous year  
- Cost 38% lower than forecast  
- ESG report ready within 4 hours of event end

## Scenario 2: "CSRD Audit Surprise"

**Context**  
Regulator requests full Scope 3 emissions proof with 10-day notice.

**GreenOps Response**  
- One-click report generation from immutable logs  
- Full traceability from workload → region → carbon intensity → final report  
- Zero manual spreadsheet work

**Outcome**  
- Report delivered in 2 hours  
- Zero findings from auditor  
- Board receives automated monthly version going forward

## Scenario 3: "Cost Overrun Alert"

**Context**  
Dev team accidentally spins up 500 extra-large VMs → projected €180k overspend.

**GreenOps Response**  
- Immediate alert + auto-rightsizing recommendation  
- One-click approval → instances resized in < 10 min  
- Prevented €162k waste

**Status**: All scenarios validated in stakeholder workshops — Dec 2025
