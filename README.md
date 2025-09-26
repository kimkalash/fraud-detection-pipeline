# Fraud Detection Pipeline

A project to build a **real-time credit card fraud detection system** combining batch and streaming data.

## Project Structure
- `data/` → raw datasets (ignored in Git)
- `notebooks/` → Jupyter notebooks for exploration & experiments
- `src/` → production-ready scripts (ETL, training, streaming, API)
- `tests/` → unit tests & pipeline checks
- `docs/` → documentation, architecture diagrams, notes

## Roadmap
1. Data exploration & feature engineering (notebooks)
2. Batch fraud detection pipeline (ETL + Postgres + model training)
3. Real-time streaming pipeline (Kafka + Spark/Flink + API)
4. Deployment & monitoring (Docker/Kubernetes, Prometheus, Grafana)

## Setup
Clone this repo:
```bash
git clone git@github.com:kimkalash/fraud-detection-pipeline.git
