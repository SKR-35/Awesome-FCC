# Awesome-FCC

A curated list of Financial Crime Compliance (FCC) resources: transaction monitoring, trade surveillance, e-comms surveillance, fraud detection, case management, sanctions screening, KYC/KYB, graph analytics, datasets, regulations and more.

FCC spans AML/CFT, sanctions, AB&C, market abuse, fraud and investigative tooling. This list aims to be practical, vendor-neutral and signal-rich.

## Table of Contents

- [Vendor / Commercial Platforms](#vendor--commercial-platforms)
- [Transaction Monitoring (AML)](#transaction-monitoring-aml)
- [Trade Surveillance (Market Abuse)](#trade-surveillance-market-abuse)
- [E-Comms / Conduct Surveillance](#e-comms--conduct-surveillance)
- [Fraud Detection](#fraud-detection)
- [Sanctions & Screening](#sanctions--screening)
- [KYC / KYB / Customer Risk](#kyc--kyb--customer-risk)
- [Case Management & Investigation](#case-management--investigation)
- [Graph & Link Analysis](#graph--link-analysis)
- [Entity Resolution & Master Data](#entity-resolution--master-data)
- [Data Ingestion, ETL & Quality](#data-ingestion-etl--quality)
- [Synthetic Data & Simulators](#synthetic-data--simulators)
- [Explainability & Model Risk](#explainability--model-risk)
- [Benchmarks & Datasets](#benchmarks--datasets)
- [Regulations, Standards & Typologies](#regulations-standards--typologies)

## Vendor / Commercial Platforms

Commercial tools are useful for discovery:

- Oracle Financial Crime and Compliance Management (FCCM) Solutions - Enterprise AML transaction monitoring/Mantas & case mgmt.

	- <a href="https://www.oracle.com/financial-services/aml-financial-crime-compliance/" target="_blank" rel="noopener noreferrer">Official Page</a>

- NICE Actimize - Cross-domain FCC suite (AML, fraud, trade/e-comms).

	- <a href="https://www.niceactimize.com/" target="_blank" rel="noopener noreferrer">Official Page</a>

- SAS AML / Fraud - Analytics-driven FCC platform.

	- <a href="https://www.sas.com/en_us/home.html" target="_blank" rel="noopener noreferrer">Official Page</a>
	
	- <a href="https://github.com/sassoftware" target="_blank" rel="noopener noreferrer">GitHub</a>

- SymphonyAI NetReveal - AML, fraud and KYC risk.

	- <a href="https://www.symphonyai.com/financial-services/netreveal-transaction-monitoring/" target="_blank" rel="noopener noreferrer">Official Page</a>
	
	- <a href="https://github.com/symphonyai-accelerate" target="_blank" rel="noopener noreferrer">GitHub</a>

- Quantexa - Entity resolution & network analytics.

	- <a href="https://www.quantexa.com/" target="_blank" rel="noopener noreferrer">Official Page</a>

- Featurespace - Adaptive behavioral fraud analytics.

	- <a href="https://www.featurespace.com/" target="_blank" rel="noopener noreferrer">Official Page</a>
	
	- <a href="https://github.com/Featurespace" target="_blank" rel="noopener noreferrer">GitHub</a>

- Behavox / Shield / Smarsh - E-comms surveillance stacks.

	- <a href="https://www.behavox.com/" target="_blank" rel="noopener noreferrer">Behavox Official Page</a>
	
	- <a href="https://www.shieldfc.com/" target="_blank" rel="noopener noreferrer">Shield Official Page</a>
	
	- <a href="https://www.smarsh.com/" target="_blank" rel="noopener noreferrer">Smarsh Official Page</a>
	
	- <a href="https://github.com/smarsh" target="_blank" rel="noopener noreferrer">Smarsh GitHub</a>

- Solidus / ACA / QuestDB - Trade surveillance.

	- <a href="https://www.soliduslabs.com/solutions/trade-surveillance" target="_blank" rel="noopener noreferrer">Solidus Official Page</a>
	
	- <a href="https://www.acaglobal.com/technology/surveillance-monitoring/market-abuse-surveillance/" target="_blank" rel="noopener noreferrer">ACA Official Page</a>
	
	- <a href="https://questdb.com/glossary/real-time-trade-surveillance/" target="_blank" rel="noopener noreferrer">QuestDB Official Page</a>
	
	- <a href="https://github.com/questdb" target="_blank" rel="noopener noreferrer">QuestDB GitHub</a>
	
- Elliptic - Wallet & transaction screening for AML compliance

	- <a href="https://www.elliptic.co/solutions/screening" target="_blank" rel="noopener noreferrer">Official Page</a>

## Transaction Monitoring (AML)

- Apache Flink - Streaming engine for real-time TM pipelines. 
	- <a href="https://github.com/apache/flink" target="_blank" rel="noopener noreferrer">GitHub</a>

## Trade Surveillance (Market Abuse)

- TimescaleDB - Time-series SQL for order book analytics.

	- <a href="https://github.com/timescale/timescaledb" target="_blank" rel="noopener noreferrer">GitHub</a>

## E-Comms / Conduct Surveillance

- spaCy / Hugging Face - NLP pipelines for policy violations, collusion cues.

	- <a href="https://github.com/explosion/spaCy" target="_blank" rel="noopener noreferrer">spaCy GitHub</a>
	
	- <a href="https://github.com/huggingface" target="_blank" rel="noopener noreferrer">Hugging Face GitHub</a>

## Fraud Detection

- PyOD - Outlier detection toolbox for fraud features.

	- <a href="https://github.com/yzhao062/pyod" target="_blank" rel="noopener noreferrer">GitHub</a>

- River - Online ML for streaming fraud detection.

	- <a href="https://riverml.xyz/" target="_blank" rel="noopener noreferrer">Official Page</a>

	- <a href="https://github.com/online-ml/river" target="_blank" rel="noopener noreferrer">River GitHub</a>

- XGBoost / LightGBM - Gradient boosting baselines for tabular fraud.

	- <a href="https://github.com/dmlc/xgboost" target="_blank" rel="noopener noreferrer">xgboost GitHub</a>
	
	- <a href="https://github.com/microsoft/LightGBM" target="_blank" rel="noopener noreferrer">LightGBM GitHub</a>

## Sanctions & Screening

- OpenSanctions - Sanctions & PEPs knowledge graph + entity data pipelines.

	- <a href="https://www.opensanctions.org/" target="_blank" rel="noopener noreferrer">Official Page</a>
	
	- <a href="https://github.com/opensanctions/opensanctions" target="_blank" rel="noopener noreferrer">GitHub</a>

- FuzzyWuzzy / RapidFuzz - Name-matching baseline.

	- <a href="https://github.com/seatgeek/fuzzywuzzy" target="_blank" rel="noopener noreferrer">FuzzyWuzzy GitHub</a>
	
	- <a href="https://github.com/rapidfuzz/RapidFuzz" target="_blank" rel="noopener noreferrer">RapidFuzzy GitHub</a>

- OFAC SDN & Consolidated Lists - Official lists + update cadence, formats.

	- <a href="https://sanctionslist.ofac.treas.gov/Home/ConsolidatedList" target="_blank" rel="noopener noreferrer">Official Page</a>

## KYC / KYB / Customer Risk

- Great Expectations - Data quality gates for KYC feeds.

	- <a href="https://github.com/great-expectations/great_expectations" target="_blank" rel="noopener noreferrer">GitHub</a>

## Case Management & Investigation

- Kibana/Elasticsearch - Query, pivot and visualize alert context.

	- <a href="https://github.com/elastic/kibana" target="_blank" rel="noopener noreferrer">Kibana GitHub</a>
	
	- <a href="https://github.com/elastic/elasticsearchs" target="_blank" rel="noopener noreferrer">ElasticsearchGitHub</a>

## Graph & Link Analysis

- NetworkX - Graph feature engineering (centrality, motifs).

	- <a href="https://github.com/networkx/networkx" target="_blank" rel="noopener noreferrer">GitHub</a>

- Neo4j - Labeled-property graph DB for rings & money-mules.

	- <a href="https://github.com/neo4j/neo4j" target="_blank" rel="noopener noreferrer">GitHub</a>

- Memgraph - Real-time graph with Cypher for streaming rings.

	- <a href="https://github.com/memgraph/memgraph" target="_blank" rel="noopener noreferrer">GitHub</a>

- Graphistry - GPU visual analytics on alert clusters.

	- <a href="https://github.com/graphistry" target="_blank" rel="noopener noreferrer">GitHub</a>

## Entity Resolution & Master Data

- Splink - Probabilistic entity resolution at scale.

	- <a href="https://github.com/moj-analytical-services/splink" target="_blank" rel="noopener noreferrer">GitHub</a>

## Data Ingestion, ETL & Quality

- Airflow - Batch orchestration for FCC pipelines.

	- <a href="https://github.com/apache/airflow" target="_blank" rel="noopener noreferrer">GitHub</a>

## Synthetic Data & Simulators

- SDV (Synthetic Data Vault) - Tabular synthetic data generation for model dev.

	- <a href="https://github.com/sdv-dev/SDV" target="_blank" rel="noopener noreferrer">GitHub</a>

- Gretel / YData - Tools to generate privacy-preserving FCC datasets.

	- <a href="https://github.com/gretelai/gretel-synthetics" target="_blank" rel="noopener noreferrer">Gretel GitHub</a>
	
	- <a href="https://github.com/ydataai" target="_blank" rel="noopener noreferrer">YData GitHub</a>

## Explainability & Model Risk

- SHAP - Local/global explanations for FCC models

	- <a href="https://github.com/shap/shap" target="_blank" rel="noopener noreferrer">GitHub</a>

## Benchmarks & Datasets

- IEEE-CIS Fraud - Financial transactions fraud dataset (imbalanced).

	- <a href="https://www.kaggle.com/competitions/ieee-fraud-detection" target="_blank" rel="noopener noreferrer">Kaggle</a>

- Elliptic Bitcoin AML - Crypto AML labels for addresses/tx.

	- <a href="https://www.elliptic.co/media-center/elliptic-releases-bitcoin-transactions-data" target="_blank" rel="noopener noreferrer">Official Page</a>
	
	- <a href="https://www.kaggle.com/datasets/ellipticco/elliptic-data-set" target="_blank" rel="noopener noreferrer">Kaggle</a>

## Regulations, Standards & Typologies

- FATF - Recommendations & typology reports (AML/CFT)

	- <a href="https://www.fatf-gafi.org/en/publications/Fatfrecommendations/Fatf-recommendations.html" target="_blank" rel="noopener noreferrer">Official Page</a>