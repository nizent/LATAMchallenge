# Data Platform Team Lead - Technical Challenge

## Diagram in architecture.jpeg

## Description in description.pdf

## Scenario: Federated Data Ingestion & Processing on GCP
You've recently joined a global airline group operating in multiple regions. Each region has developed its own local data infrastructure, storing data in regional GCP projects across various formats and systems, including BigQuery, Cloud Storage, and some PostgreSQL on CloudSQL instances.

The leadership team is pushing to enable cross-regional analytics for core business metrics like route profitability, fuel efficiency, and customer satisfaction. However, data silos, inconsistent schemas, and latency issues have made it difficult to build a unified, scalable analytics platform.

## Requirements

You are tasked with designing and leading the implementation of a federated data ingestion and processing framework that supports:

Real-time and batch ingestion from heterogeneous sources (BigQuery, GCS, PostgreSQL on CloudSQL).

Federated querying capabilities across multiple GCP projects.

Schema harmonization and data governance enforcement.

Efficient data processing pipelines for both exploratory and scheduled analytics

## Deliverable

A diagram and a brief description (1–2 pages) GCP services used (e.g., Dataflow, BigQuery Omni, Pub/Sub, Cloud Functions, Dataplex, etc.)

How data will be ingested, cataloged, and processed across regions
How you'd manage schema consistency and versioning
How you would approach cross-region query performance and cost optimization
Any trade-offs and fallback strategies (e.g., caching, materialized views)

## Instructions
1. Your solution must be in a public GitHub repository.
2. To submit your challenge, you must make a `POST` request to `https://advana-challenge-check-api-cr-k4hdbggvoq-uc.a.run.app/data-engineer`. This is an example of the body you must send:
```json
    {
      "name": "Juan Perez",
      "mail": "juan.perez@example.com",
      "github_url": "https://github.com/juanperez/latam-challenge.git"
    }
```

PLEASE, SEND THE REQUEST ONLY ONCE.
If your request was successful, you will receive this message:

```
jsonCopiar{
  "status": "OK",
  "detail": "your request was received"
}
```
