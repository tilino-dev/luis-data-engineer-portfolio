# Luis Villaseñor – Data Engineer Portfolio

Welcome to my Data Engineering portfolio.  
Here you’ll find a curated selection of projects that showcase my ability to design, build, and operate scalable data solutions using **ETL** and **ELT** approaches, API integrations, orchestration, and modern cloud data platforms.

---

## 📂 Projects

### 1) **hubspot-api-etl**
**Type:** ETL – API Integration → Postgres/S3  
**Tech:** Python, HubSpot API, PostgreSQL, AWS S3, GitHub Actions  
**What it shows:** Private-app token auth, pagination & retries, transforms to tidy tables, Postgres upserts, optional S3 Parquet export, CI scheduling.  
[**View Repository »**](https://github.com/tilino-dev/hubspot-api-etl)

---

### 2) **etl-pipeline-airflow-aws**
**Type:** ETL – Batch Pipeline with Orchestration  
**Tech:** Python, Apache Airflow, AWS S3, AWS RDS (PostgreSQL)  
**What it shows:** Airflow DAG design (extract → transform → load), task dependencies, scheduling, and AWS integration patterns.  
[**View Repository »**](https://github.com/tilino-dev/etl-pipeline-airflow-aws)

---

### 3) **data-engineer-spark-lakehouse-demo**
**Type:** ETL – PySpark Lakehouse (Bronze → Silver → Gold)  
**Tech:** PySpark, Parquet, Great Expectations, Airflow (DAG), GitHub Actions  
**What it shows:** Distributed processing with Spark, layered lakehouse modeling, partitioning & performance patterns, data quality checks, CI.  
[**View Repository »**](https://github.com/tilino-dev/data-engineer-spark-lakehouse-demo)

---

### 4) **elt-dbt-warehouse-demo**
**Type:** ELT – Transform-in-Warehouse  
**Tech:** dbt, DuckDB (swap to Snowflake/BigQuery/Redshift), SQL, GitHub Actions  
**What it shows:** Modern ELT with dbt (staging + marts), schema tests, lineage/docs, warehouse-first transformations.  
[**View Repository »**](https://github.com/tilino-dev/elt-dbt-warehouse-demo)

---

### 5) **youtube-semantic-search**
**Type:** Analytics/ML feature engineering + search  
**Tech:** Python, Sentence Transformers (embeddings), FAISS/Annoy (vector index), Streamlit (demo UI)  
**What it shows:** Building an embeddings pipeline to index YouTube titles/descriptions/transcripts and perform semantic search; batching & persistence, simple retrieval evaluation.  
[**View Repository »**](https://github.com/tilino-dev/youtube-semantic-search)

---

### 6) **affirm-ts-foundations-demo**
**Type:** Backend Foundations (Trust & Safety)  
**Tech:** FastAPI, MySQL (SQLAlchemy), Redis (rate limiter/counters), Prometheus metrics, Docker/K8s, CI  
**What it shows:** Risk state machine, vendor adapters, rate limiter, counters, audit logs, metrics; aligns with T&S platform building blocks.  
[**View Repository »**](https://github.com/tilino-dev/affirm-ts-foundations-demo)

---

## 🛠 Skills Demonstrated
- **Pipelines:** Airflow DAGs, dbt models, PySpark jobs, CI/CD
- **ETL & ELT:** When to use each; layered lakehouse and in-warehouse transforms
- **Cloud & Warehouses:** AWS (S3, RDS), Snowflake/BigQuery/Redshift-ready SQL
- **Data Modeling:** Staging, dimensions, facts; star schema
- **Quality & Observability:** Great Expectations, Prometheus-style metrics, logs
- **APIs & Integrations:** HubSpot CRM, vendor adapter patterns
- **Search/ML Adjacent:** Vector embeddings & semantic retrieval
- **Tooling:** Git/GitHub, GitHub Actions, Docker/K8s basics

---

## 📬 Contact
- **Email:** luismigueldf@hotmail.com  
- **LinkedIn:** https://linkedin.com/in/luis-villasenor-it  
- **GitHub:** https://github.com/tilino-dev

---

> 💡 This portfolio is updated regularly with new projects and improvements.
