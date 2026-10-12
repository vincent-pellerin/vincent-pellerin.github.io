+++
title = "Projets"
slug = "projects"
description = "Réalisations data en production, prototypes IA et projets expérimentaux - Vincent Pellerin, AI Data Engineer"
date = "2026-10-12"
lastmod = "2026-10-12"
+++

Les projets sont classés par maturité : ce qui tourne en production ou a été
livré à un client, ce qui reste expérimental, et ce qui est en pause ou arrêté.
Une réalisation ne signifie pas qu'un service est encore actif aujourd'hui.

## Production et réalisations client

### Plateforme de veille emploi (job_scraping)

- **Finalité** : acquérir et consolider les offres tech pour l'analyse de marché
- **Contribution** : conception et exploitation d'une plateforme à 14 sources,
  ingestion dlt, transformation dbt, stockage BigQuery sur GCP, orchestration Airflow
- **État** : en production, accès public
- **Lien** : [jobs.vpdata.fr](https://jobs.vpdata.fr/)
- **Limite** : dépendance au cloud GCP et à des APIs externes de scoring, pas
  souverain de bout en bout
- **Technologies** : Python, dlt, dbt, BigQuery, GCP, Airflow, DuckDB

### Agrégateur immobilier - Immo-Stras

- **Finalité** : suivre les annonces immobilières à Strasbourg
- **Contribution** : scraping LeBonCoin avec filtrage géographique, dashboard
  FastAPI, déduplication exacte et floue, déploiement Docker et Traefik
- **État** : réalisation ; accès authentifié, pas une démonstration publique
- **Technologies** : Python, FastAPI, SQLAlchemy, Docker, Traefik

### Mission client - Les Bredelers (2025)

- **Finalité** : structurer la donnée marketing du groupe pour piloter sa
  présence en ligne
- **Contribution** : ingestion YouTube Analytics et Meta Graph API vers BigQuery,
  transformations dbt, orchestration GitHub Actions
- **État** : réalisation client livrée
- **Technologies** : Python, dlt, dbt, BigQuery, YouTube Analytics API, Meta Graph API

### Web analytics - OTM Festival (2025)

- **Finalité** : mesurer l'audience et les ventes du festival
- **Contribution** : déploiement de Matomo en on-premise, suivi des visites,
  gestion du consentement RGPD, analyse des ventes
- **État** : réalisation
- **Technologies** : Matomo, Docker, VPS, RGPD

## Études indépendantes

### Étude - professionnels du spectacle vivant (2025)

- **Finalité** : lire l'effet du COVID sur le secteur du spectacle vivant
- **Contribution** : nettoyage et analyse de données (BigQuery, SQL, Google
  Sheets), segmentation, visualisations (Datawrapper)
- **État** : étude indépendante
- **Technologies** : BigQuery, SQL, Google Sheets, Datawrapper

## Prototypes et travaux expérimentaux

### RAG local - chemin documentaire (POC)

- **Finalité** : interroger un corpus documentaire local
- **Contribution** : chaîne Ollama, LlamaIndex, FAISS et SQLite ; le projet global
  prévoit aussi des options cloud
- **État** : prototype, pas en production
- **Technologies** : Ollama, LlamaIndex, FAISS, SQLite, Python

### Benchmarks d'agents

- **Finalité** : comparer le comportement de délégation d'agents LLM
- **Contribution** : protocoles expérimentaux et résultats empiriques
- **État** : travaux expérimentaux
- **Technologies** : Python, APIs LLM, protocoles de test

### Base de connaissance Obsidian (obsidian-wiki)

- **Finalité** : transformer un corpus documentaire en base consultable
- **Contribution** : génération de fiches, recherche hybride texte et vectorielle,
  embeddings sur GPU local
- **État** : réalisation
- **Technologies** : Python, API LLM, recherche hybride, Obsidian

### Second Brain Workflow

- **Finalité** : transformer des sources hétérogènes en notes structurées
- **Contribution** : pipeline multi-sources (vidéos, articles) vers Obsidian,
  résumés par LLM, interface Telegram, déploiement VPS avec suivi d'état
- **État** : réalisation
- **Technologies** : Python, API LLM, yt-dlp, Telegram Bot API, Obsidian

### Analyse de marché automobile (Tesla)

- **Finalité** : suivre les prix et l'état des véhicules d'occasion
- **Contribution** : acquisition de données, déduplication, commandes CLI de suivi
- **État** : réalisation
- **Technologies** : Python, DuckDB, Pydantic, Typer

## Projets en pause ou arrêtés

### Cognitive Framework - expérimentation S1/S2 (en pause)

- **Finalité** : explorer une architecture d'agents inspirée des systèmes 1 et 2
- **Contribution** : mémoire SQLite/FTS5, serveur MCP, profils d'agents
- **État** : en pause depuis plusieurs mois
- **Technologies** : Python, SQLite, MCP, LLM

### Deep Research - agent LangGraph (arrêté)

- **Finalité** : produire des rapports de recherche vérifiés
- **Contribution** : graphe LangGraph, validation humaine, checkpoints, contrôle
  de budget
- **État** : arrêté
- **Technologies** : LangGraph, LangChain, Python
