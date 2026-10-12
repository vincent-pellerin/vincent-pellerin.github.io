+++
title = "Projects"
slug = "projects"
description = "Data work in production, AI prototypes and experimental projects - Vincent Pellerin, AI Data Engineer"
date = "2026-10-12"
lastmod = "2026-10-12"
+++

Projects are grouped by maturity : what runs in production or was delivered to
a client, what is still experimental, and what is paused or stopped. A delivery
does not mean a service is still active today.

## Production and client work

### Job market platform (job_scraping)

- **Purpose** : acquire and consolidate tech job listings for market analysis
- **Contribution** : designed and operated a platform with 14 sources, dlt
  ingestion, dbt transformation, BigQuery storage on GCP, Airflow orchestration
- **Status** : in production, public access
- **Link** : [jobs.vpdata.fr](https://jobs.vpdata.fr/)
- **Limit** : depends on GCP cloud and external scoring APIs, not end-to-end
  sovereign
- **Technologies** : Python, dlt, dbt, BigQuery, GCP, Airflow, DuckDB

### Real estate aggregator - Immo-Stras

- **Purpose** : track real estate listings in Strasbourg
- **Contribution** : LeBonCoin scraping with geographic filtering, FastAPI
  dashboard, exact and fuzzy deduplication, Docker and Traefik deployment
- **Status** : delivered ; authenticated access, not a public demo
- **Technologies** : Python, FastAPI, SQLAlchemy, Docker, Traefik

### Client mission - Les Bredelers (2025)

- **Purpose** : structure the band's marketing data to steer its online presence
- **Contribution** : YouTube Analytics and Meta Graph API ingestion to BigQuery,
  dbt transformations, GitHub Actions orchestration
- **Status** : delivered client work
- **Technologies** : Python, dlt, dbt, BigQuery, YouTube Analytics API, Meta Graph API

### Web analytics - OTM Festival (2025)

- **Purpose** : measure the festival's audience and ticket sales
- **Contribution** : on-premise Matomo deployment, visit tracking, GDPR consent
  management, sales analysis
- **Status** : delivered
- **Technologies** : Matomo, Docker, VPS, GDPR

## Independent studies

### Study - performing arts professionals (2025)

- **Purpose** : read the effect of COVID on the live performance sector
- **Contribution** : data cleaning and analysis (BigQuery, SQL, Google Sheets),
  segmentation, visualisations (Datawrapper)
- **Status** : independent study
- **Technologies** : BigQuery, SQL, Google Sheets, Datawrapper

## Prototypes and experimental work

### Local RAG - document chain (proof of concept)

- **Purpose** : query a local document corpus
- **Contribution** : Ollama, LlamaIndex, FAISS and SQLite chain ; the wider
  project also plans cloud options
- **Status** : prototype, not in production
- **Technologies** : Ollama, LlamaIndex, FAISS, SQLite, Python

### Agent benchmarks

- **Purpose** : compare the delegation behaviour of LLM agents
- **Contribution** : experimental protocols and empirical results
- **Status** : experimental work
- **Technologies** : Python, LLM APIs, test protocols

### Obsidian knowledge base (obsidian-wiki)

- **Purpose** : turn a document corpus into a searchable knowledge base
- **Contribution** : note generation, hybrid text and vector search, embeddings on
  a local GPU
- **Status** : delivered
- **Technologies** : Python, LLM API, hybrid search, Obsidian

### Second Brain Workflow

- **Purpose** : turn heterogeneous sources into structured notes
- **Contribution** : multi-source pipeline (videos, articles) to Obsidian, LLM
  summaries, Telegram interface, VPS deployment with state tracking
- **Status** : delivered
- **Technologies** : Python, LLM API, yt-dlp, Telegram Bot API, Obsidian

### Car market analysis (Tesla)

- **Purpose** : track prices and condition of used vehicles
- **Contribution** : data acquisition, deduplication, CLI commands for tracking
- **Status** : delivered
- **Technologies** : Python, DuckDB, Pydantic, Typer

## Paused or stopped projects

### Cognitive Framework - S1/S2 experiment (paused)

- **Purpose** : explore an agent architecture inspired by systems 1 and 2
- **Contribution** : SQLite/FTS5 memory, MCP server, agent profiles
- **Status** : paused for several months
- **Technologies** : Python, SQLite, MCP, LLM

### Deep Research - LangGraph agent (stopped)

- **Purpose** : produce verified research reports
- **Contribution** : LangGraph graph, human validation, checkpoints, budget control
- **Status** : stopped
- **Technologies** : LangGraph, LangChain, Python
