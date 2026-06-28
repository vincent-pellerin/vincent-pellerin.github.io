+++
title = "Projets"
slug = "projects"
+++

## 2026

### Data Pipelines & Automatisation

**Job Market Intelligence Engine** `[repo privé]`
- **13 plateformes** de recrutement analysées quotidiennement
- **~7 800 offres** d'emploi tech agrégées dans 2 bases DuckDB
- Pipeline CI/CD 3 étapes (lint → test → deploy) — **222 tests**
- Serveur MCP exposant les données en temps réel aux agents IA
- Python · dlt · DuckDB · FastMCP · pydantic · typer · loguru

**Deep Research Agent** `[repo privé]`
- Pipeline agentic LangGraph **9-10 nœuds** : recherche → vérification → synthèse
- **3 LLMs** orchestrés (Gemini 2.5 Pro, DeepSeek V4, DeepSeek Chat)
- Fetching parallèle : **5 URLs simultanées** avec régulation (Semaphore)
- Rapports markdown structurés générés automatiquement **3x/semaine** (cron Docker VPS)
- **170 tests** · LangGraph · LangChain · Serper · httpx · Docker

**Knowledge Base Automation** `[repo privé]`
- Vault Obsidian **43 000+ documents** — second cerveau personnel
- **37 000+ fiches** wiki générées automatiquement par LLM
- Recherche hybride BM25 + vectoriel (QMD) · embeddings GPU (ROCm, RX 7800 XT)
- Multi-provider LLM (Gemini, Inception Labs)
- Python · Gemini API · QMD · Obsidian

### Web Scraping & Données de Marché

**Immo-Stras — Agrégateur Immobilier** [GitHub][immolink]
- En production depuis 2025 : **[immo.vpdata.fr][immosite]**
- Scraping LeBonCoin avec filtrage géographique (Strasbourg, 5 codes postaux)
- Dashboard web FastAPI + déduplication intelligente (matching exact + fuzzy)
- Déploiement Docker + Traefik + HTTPS · CI/CD GitHub Actions · intégration n8n
- FastAPI · SQLAlchemy · Docker · Traefik · n8n

**Tesla Market Analyzer** `[repo privé]`
- Analyse de marché automatisée : prix, kilométrage, état de batterie
- **237 tests** unitaires avec isolation complète des bases (DuckDB/SQLite)
- CI/CD GitHub Actions + notifications Discord
- **17 commandes** CLI (Typer + Rich) : stats, best-deals, report
- Python · DuckDB · Pydantic · Typer · GitHub Actions

### Outils & Infrastructure

**Cognitive Framework** `[repo privé]`
- Architecture hybride S1/S2 pour agents de codage — **1 148 tests** passants
- **6 types** de projets gérés automatiquement (web, api, data, cli, lib, bot)
- Serveur MCP 7 outils (FastMCP/stdio) · profils installables
- LangGraph · LangChain · Pydantic · pytest · FastMCP

**Second Brain Workflow** `[repo privé]`
- Pipeline multi-sources (YouTube, Medium, articles web) → notes Obsidian structurées
- **5 phases** de développement · **~10 000 lignes** Python · **336 fonctions**
- Résumés IA via Gemini 2.5 Flash (contexte 1M tokens)
- Interface Telegram : commandes /batch, /enrich, /index
- Anti-détection : rotation proxy Webshare, cookie management
- Support multi-langues avec fallback automatique (fr → en)
- Déploiement VPS avec systemd · pipeline state tracking
- Python · Gemini API · yt-dlp · Telegram Bot API · Obsidian

## 2025

### Data Analyst & Digital Marketer [Les Bredelers][bredlink]

Recherche de données optimales pour le développement du groupe\
Tracking des visiteurs sur le site (matomo analytics)\
Évaluation de la performance de contenu sur les réseaux sociaux (Youtube & Meta)\
Développement stratégique : retours et conseils\

**Social Media Analytics Pipeline** `[repo privé]`
- Pipeline ELT unifié YouTube + Meta : ingestion dlt, transformations dbt
- Modèle OBT **~2 300 lignes** dans BigQuery, 4 datasets
- Orchestration GitHub Actions (3 runs/jour)
- Python · dlt · dbt · BigQuery · YouTube API · Meta Graph API

### Tracking [OTM festival][otmlink]

Installation Matomo Analytics sur un VPS personnel\
Suivi des visites\
Analyse des ventes\
...

### [Étude des professionnels du spectacle vivant][etudelink]

Effondrement du secteur du spectacle vivant suite au COVID (2025)\
Impact du COVID-19 sur le secteur du spectacle vivant : - 80% de renouvellements de licences\
Nettoyage et analyse de 80.000 lignes avec BigQuery, SQL et Google Sheets\
Segmentation des données pour isoler les acteurs majeurs du secteur\
Visualisations graphiques : cartes, graphiques, tableaux (Datawrapper, Google Sheet)\
Identification des secteurs dominants et des types d'utilisateurs clés (par exemple, individuels contre autres personnes physiques)

[immolink]: https://github.com/vincent-pellerin/immo-stras
[immosite]: https://immo.vpdata.fr
[otmlink]: https://otmfestival.fr
[etudelink]: https://pitch.com/v/etude-march-professionnels-spectacle-vivant-sg8287?ref=portf0lio
[bredlink]: https://www.bredelers.com
