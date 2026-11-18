<div align="center">

# Hi there, I'm Sreya Peddu 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2E9CD3&center=true&vCenter=true&width=700&lines=Senior+Data+Engineer;Python+%E2%80%A2+SQL+%E2%80%A2+PySpark+%E2%80%A2+Databricks;Spark+%E2%80%A2+Kafka+%E2%80%A2+Airflow+%E2%80%A2+dbt;Lakehouse+%E2%80%A2+Snowflake+%E2%80%A2+Delta+Lake;I+build+data+platforms+that+scale)](https://git.io/typing-svg)

**Senior Data Engineer — Dallas–Fort Worth, TX**

[LinkedIn](https://www.linkedin.com/in/sreyapeddu) • peddusreya02@gmail.com • +1 (940) 597-0416

</div>

---

## 👩‍💻 About Me

Senior Data Engineer with nearly **5 years** of experience designing and building scalable, distributed data platforms, data lakehouse and medallion architectures, and cloud data warehouses for **healthcare and financial services**.

I deliver production **ETL/ELT pipelines** across **AWS, Azure, and GCP** that process terabytes of data daily — with deep experience in dimensional modeling, CDC and incremental processing, data migration, Git-based CI/CD, data quality, monitoring and observability, performance and cost optimization, and data governance and security for **HIPAA- and SOX-regulated data**.

I also build data foundations for generative AI and machine learning — **RAG pipelines, embeddings, vector databases, and MLflow-tracked features** — and partner with stakeholders, analysts, and data scientists to deliver trusted, analytics-ready data.

- 🏥 **Tenet Healthcare** — Senior Data Engineer, Jan 2025 – Present, Dallas, TX
- 📈 **Bloomberg** — Data Engineer, Apr 2022 – Aug 2023, Hyderabad, India
- 🏦 **State Street Bank** — Data Engineer, Nov 2020 – Mar 2022, Hyderabad, India

---

## 💼 Experience Highlights

### Tenet Healthcare — Senior Data Engineer
- End-to-end ETL/ELT in **Python, SQL, and PySpark** on **Databricks** and Dataproc, ingesting clinical, claims, and operational data from 30+ EHR, SQL Server, and REST API sources (~1 TB/day) into a **Delta Lake lakehouse** on GCP and BigQuery, with Azure Data Factory and Microsoft Fabric feeds
- **dbt** models with incremental materializations and CDC-based loads — cutting load times by ~50%
- Spark / Spark SQL optimization (partitioning, caching, broadcast joins, Delta OPTIMIZE/Z-ORDER) — ~35% lower batch runtimes and Databricks cost
- **Apache Airflow** DAGs on Cloud Composer: scheduling, SLA alerts, retries, backfills, on-call production support and root-cause analysis
- Fault-tolerant **Apache Kafka** ingestion for real-time clinical event streams — Schema Registry, schema evolution, checkpointing
- Dimensional models (star schema, **SCD Type 2**) for patient, encounter, provider, and care-event data across Bronze / Silver / Gold medallion layers
- **Terraform** infrastructure as code + **GitHub Actions CI/CD** with unit and pipeline testing
- HIPAA controls on PHI — tokenization, masking, encryption, RBAC via **Unity Catalog**; HL7/FHIR validation with **Great Expectations** and dbt tests
- GenAI/ML pipelines: RAG over de-identified clinical documentation (chunking, embeddings, vector database) and PySpark feature engineering tracked in **MLflow** for readmission-risk models

### Bloomberg — Data Engineer
- Distributed **Python and PySpark** pipelines on Apache Spark for pricing, reference data, and corporate actions
- **Kafka** ingestion for real-time market data — tens of millions of events/day, partition-aware consumers, Schema Registry, offset handling
- Stateful streaming in Scala and Java with **Spark Structured Streaming** and **Apache Flink**
- Airflow orchestration, **Great Expectations + Monte Carlo** data quality and observability
- GenAI pipelines embedding financial filings and news corpora into vector databases for RAG-powered search and summarization
- Transformation jobs on HBase, MySQL, and PostgreSQL, served via internal REST APIs; **Docker / Kubernetes** deployments

### State Street Bank — Data Engineer
- PySpark ETL/ELT on **Amazon EMR** and Databricks, with **AWS DMS CDC** from on-prem Oracle and SQL Server — on-prem to cloud migration of custody data into **Snowflake** and S3
- Snowflake dimensional models (SCD Type 2), complex SQL and stored procedures for regulatory reporting
- Migration of legacy **Informatica** workflows to modular **dbt** models with incremental loading and automated tests
- CDC MERGE/upsert patterns on **Delta Lake and Apache Iceberg**; partition pruning and cluster right-sizing cut the batch window by ~30%
- Curated datasets to Amazon Redshift, Azure Data Factory, and Azure Synapse; cataloging and governance with **AWS Glue, Lake Formation, and IAM**; Lambda event-driven ingestion
- Python/SQL reconciliation and lineage supporting **SOX** controls; Terraform, Jenkins, Azure DevOps, and Docker delivery

---

## 🛠️ Tech Arsenal

**Programming:** Python • SQL • Spark SQL • PySpark • Scala • Java • Shell Scripting (Linux)

**Big Data & Lakehouse:** Apache Spark • Databricks • Delta Lake • Apache Iceberg • Data Lakehouse

**Cloud:** AWS (S3, EMR, Glue, Lambda, DMS, Lake Formation, IAM) • Azure (Data Factory, Microsoft Fabric) • GCP (Dataproc)

**Data Warehousing:** Snowflake • BigQuery • Amazon Redshift • Azure Synapse Analytics

**Data Modeling:** Dimensional Modeling • Star Schema • Fact & Dimension Tables • SCD Type 2 • Medallion Architecture (Bronze/Silver/Gold)

**Transformation:** dbt • Incremental Materializations • Complex SQL • Stored Procedures • Informatica

**Orchestration & Streaming:** Apache Airflow • Cloud Composer • Apache Kafka • Schema Registry • Spark Structured Streaming • Apache Flink

**CI/CD, Containers & IaC:** Git • GitHub Actions • Jenkins • Azure DevOps • Docker • Kubernetes • Terraform

**Data Quality & Observability:** Great Expectations • dbt Tests • Monte Carlo • Data Validation • Reconciliation • SLA Alerts

**Governance, Security & Compliance:** Unity Catalog • Data Lineage • Tokenization • Data Masking • Encryption • RBAC • HIPAA / PHI • SOX • EHR • HL7 • FHIR

**Performance:** Query Optimization • Partitioning / Partition Pruning • Caching • Broadcast Joins • OPTIMIZE/Z-ORDER • Cluster Right-Sizing

**GenAI & ML Data Engineering:** RAG • LLM Integration • Embeddings • Vector Databases • Feature Engineering • MLflow

**Databases & APIs:** SQL Server • Oracle • PostgreSQL • MySQL • HBase • REST APIs

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5D5?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Featured Projects — 5 Data Engineering + 2 GenAI

> Seven flagship portfolio projects built from scratch on **synthetic data only** — 5 data engineering, 2 GenAI implementation & engineering. Real production patterns, zero real patient, customer, or market data.

[![Healthcare Data Lakehouse](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=databricks-pyspark-etl-pipeline)](https://github.com/sreya-dataanalyst/databricks-pyspark-etl-pipeline)
[![Real-Time Streaming Ingestion](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=kafka-streaming-ingestion)](https://github.com/sreya-dataanalyst/kafka-streaming-ingestion)
[![dbt Snowflake Modeling](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=dbt-snowflake-data-modeling)](https://github.com/sreya-dataanalyst/dbt-snowflake-data-modeling)
[![Airflow ELT with Data Quality](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=airflow-orchestration-platform)](https://github.com/sreya-dataanalyst/airflow-orchestration-platform)
[![Terraform Data Platform](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=terraform-data-platform-iac)](https://github.com/sreya-dataanalyst/terraform-data-platform-iac)
[![GenAI RAG Data Pipeline](https://github-readme-stats.vercel.app/api/pin/?username=sreya-dataanalyst&repo=genai-rag-data-pipeline)](https://github.com/sreya-dataanalyst/genai-rag-data-pipeline)

### Data Engineering (5)
1. **Healthcare Data Lakehouse — Databricks + Delta Lake Medallion Architecture** — lakehouse ingestion of clinical/claims data into Bronze/Silver/Gold layers, CDC/incremental loads, Unity Catalog HIPAA governance
2. **Real-Time Streaming Ingestion — Apache Kafka + Spark Structured Streaming** — Schema Registry, schema evolution, fault-tolerant streaming for clinical and market data events
3. **dbt + Snowflake Dimensional Modeling** — star schema, SCD Type 2, incremental dbt models and tests for financial reporting and healthcare marts
4. **Airflow-Orchestrated ELT with Data Quality** — Airflow DAGs, SLA alerts, retries/backfills, Great Expectations validation, GitHub Actions CI/CD
5. **Terraform Data Platform IaC** — Terraform modules, Docker/Kubernetes, GitHub Actions / Jenkins / Azure DevOps CI/CD for cloud data platform delivery

### GenAI Implementation & Engineering (2)
6. **GenAI / RAG Data Pipeline** — document chunking, PHI de-identification, embeddings and vector database loading for LLM-powered internal search, plus MLflow-tracked PySpark feature pipelines
7. **GenAI LLM Search & Summarization — Financial Filings & News Pipeline** — [github.com/sreya-dataanalyst/genai-llm-financial-search](https://github.com/sreya-dataanalyst/genai-llm-financial-search) — parsing, chunking and embedding filings/news into vector databases for LLM-powered search and summarization

---

## 📊 GitHub Stats

<div align="center">

![Sreya's GitHub stats](https://github-readme-stats.vercel.app/api?username=sreya-dataanalyst&show_icons=true&count_private=false)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sreya-dataanalyst&layout=compact)
![GitHub Streak](https://streak-stats.demolab.com?user=sreya-dataanalyst)

</div>

---

## 🏆 Certifications

- ✅ **Databricks Certified Data Engineer Associate**
- ✅ **Microsoft Certified: Fabric Data Engineer Associate**
- ✅ **dbt Analytics Engineering**

## 🎓 Education

- **University of North Texas** — Master of Science in Data Science, May 2025
- **GITAM University** — B.Tech in Electrical, Electronics and Communication Engineering

## 💼 Open To

**Senior Data Engineer** roles — remote-first, US-wide (Texas / DFW a plus). If your team needs reliable, governed, analytics- and AI-ready data platforms, let's talk.

## 📫 Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/sreyapeddu) — fastest way to reach me
- ✉️ peddusreya02@gmail.com
- 💻 Browse the repos above — every project is documented to be explored

---

<div align="center">

![Visitor Count](https://komarev.com/ghpvc/?username=sreya-dataanalyst&color=2E9CD3)

*Thanks for stopping by — happy engineering!* ⚙️

</div>
