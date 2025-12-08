# Phase C – 02 Application Architecture

## Application Components & GCP Services

| Component                | GCP Service                  | Responsibility                              |
|--------------------------|------------------------------|---------------------------------------------|
| Ingestion Layer          | Cloud Functions + Pub/Sub    | Ingest real-time events                     |
| Carbon Intelligence      | Vertex AI + Carbon API       | Predict & score region carbon intensity     |
| Optimization Engine   | Cloud Run (containerized)    | Decision engine + scheduling logic          |
| Scheduler                | Cloud Scheduler + Compute API| Execute live migrations                     |
| Data Lakehouse           | BigQuery + Dataflow          | Storage + transformations                   |
| Reporting Engine         | Looker + Cloud Run           | Generate CSRD PDFs/XBRL                   |
| Dashboard                | Looker Studio                | Real-time FinOps + GreenOps views           |
| Audit & Governance       | Cloud Audit Logs + DLP       | Immutable logging & compliance              |

## C4 Context Diagram (Level 1)
