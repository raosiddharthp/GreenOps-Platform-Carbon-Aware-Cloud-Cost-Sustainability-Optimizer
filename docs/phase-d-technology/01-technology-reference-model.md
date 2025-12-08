# Phase D – 01 Technology Reference Model (TRM)

## GreenOps Platform TRM

| Layer                  | Component                          | GCP Service(s)                         | Standard / Version |
|------------------------|------------------------------------|----------------------------------------|--------------------|
| **Presentation**       | Dashboards & Reports               | Looker Studio, Looker                  | Latest             |
| **Application**        | Optimization Engine                | Cloud Run (Go/Python)                  | v1.28+             |
|                        | Reporting Engine                   | Cloud Run (Node.js)                    | v20                |
| **Integration**        | Event Bus                          | Pub/Sub                                | Latest             |
|                        | API Gateway                        | Cloud Endpoints or Apigee (optional)   | Latest             |
| **Data**               | Data Lakehouse                     | BigQuery                               | Enterprise         |
|                        | Streaming                          | Dataflow                               | Latest             |
| **AI/ML**              | Carbon Forecasting                 | Vertex AI Workbench + AutoML           | Latest             |
|                        | Decision Engine                    | Vertex AI Pipelines                    | Latest             |
| **Infrastructure**     | Compute                            | Compute Engine (e2, n2, c3) + Cloud Run| Latest             |
|                        | Storage                            | Cloud Storage (Standard)               | Latest             |
| **Security**           | Identity & Access                  | IAM + Workload Identity Federation     | Latest             |
|                        | Audit                              | Cloud Audit Logs (immutable)           | Enabled            |
|                        | Secrets                            | Secret Manager                         | Latest             |
| **Observability**      | Monitoring & Logging               | Cloud Monitoring + Cloud Logging       | Latest             |
| **Automation**         | IaC                                | Terraform + Config Connector           | TF 1.6+            |

**Principle**: 100% GCP-native, serverless-first, zero vendor lock-in.

**Status**: TRM approved — 20 Dec 2025
