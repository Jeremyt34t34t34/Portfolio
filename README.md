# Haipei (Jeremy) Zhong
### Applied AI · Data Engineering · Forward Deployed Engineering

I focus on connecting data, retrieval, and usable interfaces. This portfolio brings together an educational AI capstone, a team hackathon project, hands-on engineering coursework, and earlier data storytelling work.

[GitHub profile](https://github.com/Jeremyt34t34t34) · [Portfolio website](https://jeremyt34t34t34.github.io/Portfolio/)

## Featured projects

### [Biomedical Dataset Discovery Assistant](https://github.com/Jeremyt34t34t34/biomedical-dataset-discovery-assistant)
An educational capstone for finding public biomedical datasets from GDC and cBioPortal metadata.

- Normalized dataset catalog with source evidence and explicit limitations.
- Constrained keyword retrieval with TF-IDF cosine reranking; optional live OpenAI RAG.
- Streamlit reviewer UI, HTTP API, tool traces, feedback collection, and evaluation workflows.

**Scope:** study-level metadata; the local tool workflow is deterministic. Variant-positive patient counts are not verified, and this is not a production cloud deployment.

[Code](https://github.com/Jeremyt34t34t34/biomedical-dataset-discovery-assistant) · [Reviewer walkthrough](https://github.com/Jeremyt34t34t34/biomedical-dataset-discovery-assistant/blob/main/docs/reviewer_walkthrough.md) · [Retrieval implementation](https://github.com/Jeremyt34t34t34/biomedical-dataset-discovery-assistant/blob/main/src/retriever.py)

### [ClaimDrift](https://github.com/Jeremyt34t34t34/ClaimDrift)
A team project submitted to the **Google Cloud Rapid Agent Hackathon, Elastic Track**, exploring how scientific claims change between preprints and published papers.

- bioRxiv, medRxiv, and Crossref ingestion with Elasticsearch storage.
- Google ADK orchestration of claim extraction, drift analysis, citation discovery, notification, and memory synthesis.
- Python backend with REST/SSE interfaces and a Next.js dashboard.

**Context:** hackathon team work. The repository contains deployment configurations and reports a deployed demo; current service availability has not been independently verified here. Component descriptions refer to the team system, not sole authorship.

[Code & setup](https://github.com/Jeremyt34t34t34/ClaimDrift) · [Backend](https://github.com/Jeremyt34t34t34/ClaimDrift/tree/main/apps/bff) · [Orchestration code](https://github.com/Jeremyt34t34t34/ClaimDrift/blob/main/agents/supervisor_agent/agent.py)

## Engineering practice

| Repository | Concrete examples | Context |
| --- | --- | --- |
| [LLM Zoomcamp 2026 Homework](https://github.com/Jeremyt34t34t34/llm-zoomcamp-2026-homework) | ONNX MiniLM embeddings; text/vector/hybrid retrieval evaluation; OpenTelemetry RAG spans persisted to SQLite | DataTalks.Club coursework, with agentic RAG and Kestra orchestration exercises |
| [Data Engineering Zoomcamp Learning](https://github.com/Jeremyt34t34t34/data-engineering-zoomcamp-learning/tree/main/homework-submissions) | BigQuery partitioning/clustering SQL; FHV dbt staging model; homework answers and notes for modules 1–4 | Course materials plus homework submissions; not a standalone production platform |

## What to explore

- **AI:** inspect retrieval, grounding, and evaluation in the biomedical capstone.
- **Data:** review the [warehouse SQL](https://github.com/Jeremyt34t34t34/data-engineering-zoomcamp-learning/blob/main/homework-submissions/module-03-data-warehouse/homework.sql) and [dbt staging model](https://github.com/Jeremyt34t34t34/data-engineering-zoomcamp-learning/blob/main/04-analytics-engineering/taxi_rides_ny/models/staging/stg_fhv_tripdata.sql).
- **FDE:** follow the capstone's reviewer setup, API interface, source evidence, and tool trace to see how an application can be inspected and demonstrated.

## Legacy: data storytelling at CMU

My 2023 *Telling Stories with Data* assignments are preserved as earlier coursework.

[Browse the legacy collection](archive/legacy/README.md) · [Original course portfolio](archive/legacy/course-portfolio.md)
