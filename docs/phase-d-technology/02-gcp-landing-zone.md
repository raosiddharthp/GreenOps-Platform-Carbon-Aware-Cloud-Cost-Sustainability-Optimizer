# Phase D – 02 GCP Landing Zone & Standards

## GreenOps Landing Zone Design (Multi-Org Ready)

| Layer                  | Component                          | Implementation                              |
|------------------------|------------------------------------|---------------------------------------------|
| **Organization**       | Org Policy + Folder Structure      | folders: prod / non-prod / security / sandbox |
| **Identity**           | Centralized IAM                    | groups: greenops-admins, finops-viewers     |
| **Networking**         | VPC Service Controls + Hub & Spoke | Shared VPC, Private Service Connect         |
| **Security**           | Org-level Policies                 | Restrict public IPs, enforce CMEK           |
| **Billing**            | Hierarchical Budgets + Alerts      | Budget scopes per folder, auto-alerts       |
| **Logging & Monitoring** | Centralized Logging Sink          | Export all logs to central audit project    |
| **Carbon Awareness**   | Region Policy                      | Default regions: europe-west8, europe-west9 (≥85% renewable) |

## Mandatory Standards
- All workloads must run in approved low-carbon regions
- All resources auto-tagged with `environment`, `owner`, `cost-center`
- CMEK required for all storage
- No public IPs allowed
- Terraform state stored in GCS with versioning

**Visual**: [gcp-landing-zone.drawio](../diagrams/gcp-landing-zone.drawio)

**Status**: Landing zone deployed to production — 22 Dec 2025
