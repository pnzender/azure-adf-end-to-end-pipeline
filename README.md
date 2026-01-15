# Azure Data Factory – Medallion Architecture Pipeline

This project demonstrates an end-to-end Azure Data Factory (ADF) implementation following the Medallion Architecture pattern (Bronze, Silver, Gold).

The goal is to ingest data from multiple sources, store raw data in a Bronze layer, apply cleaning and standardization in a Silver layer, and produce analytics-ready datasets in a Gold layer.

## Architecture Overview

- Sources:
  - GitHub (HTTP CSV)
  - Azure SQL Database
- Orchestration:
  - Azure Data Factory
- Storage:
  - Azure Data Lake Storage Gen2
- Layers:
  - Bronze: raw, immutable data
  - Silver: cleaned and standardized data
  - Gold: aggregated and business-ready data

This repository is a learning and practice project and will evolve incrementally.
