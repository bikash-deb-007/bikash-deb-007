# Hi, I'm Bikash Deb 👋

**Data Engineer** | Building production pipelines at scale with PySpark, Delta Lake, and Databricks

---

## About Me

I build and operate data pipelines that process **millions of records per day** — from ingestion through quality validation to business-ready delivery. I've shipped 2 production pipelines at Verizon and spent 5 years at **Amazon** building evaluation pipelines for Alexa's voice AI.

**What I do:**
- **PySpark/Spark** — Distributed data processing, optimization, AQE tuning, broadcast joins, partitioning strategies
- **Delta Lake & Databricks** — Medallion Architecture (Bronze/Silver/Gold), ACID transactions, VACUUM/OPTIMIZE/MERGE, Unity Catalog
- **Data Quality** — Deduplication (0.3% rate), PII masking (SHA-256), drift detection, quarantine patterns
- **ETL/ELT** — Batch pipelines, schema-on-read validation, automated reconciliation

Currently at **Verizon Consumer Group** (via Infinite CS), building the data platform for AI model validation.

---

## Experience

### 🏢 Infinite Computer Solutions → Verizon Consumer Group
**Data Engineer** | Sep 2024 – Present | Bengaluru, India

**AI Validation Data Platform** (Jul 2025 – Present)
- Built end-to-end platform evaluating billing AI accuracy across 12 scenarios × 4 dimensions (accuracy, math correctness, relevance, clarity)
- PySpark accuracy engine processing **10M+ records/month** with deterministic PII masking and Unity Catalog access control
- Automated regression detection — caught V18 model regression (87% → 71% on proration scenarios) before production deployment
- Delivers team-specific Gold tables to 4 downstream teams (Billing SLM, Wireless Chat, VCG Digital, Model Ops)

**CDR Batch Pipeline** (Dec 2024 – Jun 2025)
- Architected Medallion pipeline processing **~1M CDR records/day** on Databricks with Delta Lake
- Reduced pipeline latency by **35%** — AQE tuning (200→38 shuffle partitions), broadcast joins, data skew handling
- Automated billing reconciliation — cut from 6 person-days/month manual Excel to daily automated detection, recovering **~$50K/month** in mischarges
- Delivered 4 Gold tables to Finance, Revenue Assurance, Network Ops, and Data Science teams

### 🏢 Amazon — Alexa Data Services
**Data Engineer** | Sep 2017 – Sep 2022 | Bengaluru, India

- Built PySpark batch pipelines processing **5M+ evaluation records/day** — comparing Alexa's ASR output against transcriber data (word error rate) and NLU predictions against annotator labels (intent match, slot F1) across 3 global centers
- Reduced pipeline latency from 4 hours to **45 minutes** (84% reduction) through partition pruning, broadcast joins, salting for skewed intents, and UDF elimination
- Built drift detection framework — 7-day rolling accuracy vs 28-day baseline, >3% delta triggers alert — caught silent quality degradation before it impacted model training
- Combined ASR + NLU + GSR (Goal Success Rate) metrics into unified pipeline, enabling ML team to identify which intents needed improved training data

---

## Technical Skills

| Category | Technologies |
|----------|-------------|
| **Data Engineering** | PySpark, Apache Spark, Delta Lake, Databricks, Medallion Architecture (Bronze/Silver/Gold) |
| **Cloud & Storage** | Azure Data Factory, ADLS Gen2, Parquet, Delta format |
| **Programming** | Python, SQL (CTEs, window functions, MERGE), Git |
| **Data Quality** | Schema validation, deduplication, PII masking (SHA-256), drift detection, quarantine patterns |
| **Performance** | AQE tuning, broadcast joins, partition pruning, data skew handling, Spark UI analysis |

---

## Projects

### 1️⃣ AI Validation Data Platform (Current)
[🔗 View Project](https://github.com/bikash-deb-007/data-engineering-profile)
> End-to-end platform for validating LLM-based billing AI at Verizon. Processes 10M+ records/month across 12 billing scenarios, tracks accuracy across model versions (V16 → V18+), and serves 4 downstream teams.

### 2️⃣ CDR Batch Pipeline
[🔗 View Project](https://github.com/bikash-deb-007/data-engineering-profile)
> Production Medallion pipeline processing 1M CDR records/day for telecom revenue assurance. Automated reconciliation recovered $50K/month in mischarges. PySpark + Delta Lake + ADF.

### 3️⃣ Amazon Alexa Evaluation Pipeline
[🔗 View Project](https://github.com/bikash-deb-007/data-engineering-profile)
> 5 years of building and optimizing evaluation pipelines for Alexa NLU training data. 5M+ records/day, 84% latency reduction, 3 global annotation centers.

---

## GitHub Stats

![Bikash's GitHub stats](https://github-readme-stats.vercel.app/api?username=bikash-deb-007&show_icons=true&theme=default&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=bikash-deb-007&layout=compact&theme=default&hide_border=true)

---

## Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-bikash--deb--007-181717?style=flat&logo=github)](https://github.com/bikash-deb-007)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-bikash--deb-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/bikash-deb)

---

> *"Data scientists get the glory, but data engineers build the foundation."*