# Hi, I'm Joaquin 👋

### Analytics Engineer | Finance & Accounting Data Systems
*Based in Peru 🇵🇪 | Analytics Engineering for Finance & Accounting*

I build data pipelines and analytical systems for financial domains — turning raw accounting and finance data into structured, queryable infrastructure that supports real business decisions.

My background in accounting and auditing (KPMG) gives me business context that complements my engineering work. **I understand what the numbers mean before I move them.**

---

## 🚀 Featured Project: [Peru Budget Lakehouse](https://github.com/DaelFame/peru-budget-lakehouse)

An end-to-end analytics pipeline engineered to process large-scale financial datasets under strict local hardware constraints — no cloud required.

### Technical Highlights
| Dimension | Detail |
| :--- | :--- |
| **Data volume** | 47M+ records · 8.5GB source |
| **Memory constraint** | Full pipeline runs on 4GB RAM via hash chunking |
| **Query performance** | Sub-second OLAP queries via DuckDB |
| **Architecture** | Bronze / Silver / Gold Medallion Lakehouse |
| **Data modeling** | Kimball Star Schema |
| **Orchestration** | Prefect pipelines with error handling |

### Core Engineering Decisions
* **DuckDB over PostgreSQL**: In-process columnar engine eliminates infrastructure overhead while delivering OLAP-grade performance locally.
* **Polars over Pandas**: Selected for memory efficiency and lazy evaluation when processing multi-GB datasets under constrained hardware resources.
* **Parquet + ZSTD**: Columnar storage reduces scan cost from 8.5GB to sub-GB effective reads.
* **Hash-chunked ingestion**: Deterministic partitioning allows full processing within 4GB RAM.

---

## 💻 Tech Stack
* **Engineering**: Python, Polars, DuckDB, SQL, Apache Parquet
* **Pipeline & Infra**: Prefect, Docker, GitHub Actions, Linux
* **Modeling & BI**: Kimball Dimensional Modeling, Star Schema, Streamlit, Matplotlib
* **Domain Knowledge**: Financial Reporting, Financial Analysis, FP&A Analytics, Audit & Assurance

![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=white)
![Polars](https://img.shields.io/badge/polars-150458?style=flat-square&logo=polars&logoColor=white)
![DuckDB](https://img.shields.io/badge/duckdb-fff000?style=flat-square&logo=duckdb&logoColor=black)
![SQL](https://img.shields.io/badge/sql-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prefect](https://img.shields.io/badge/prefect-000000?style=flat-square&logo=prefect&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![PowerBI](https://img.shields.io/badge/powerbi-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## 🔭 Currently Building
* Incremental load patterns for append-only financial transaction data.
* Data observability: pipeline run tracking and anomaly detection.
* Evaluating cloud deployment patterns for analytical workloads (BigQuery).

---

## 🌐 Connect
* **LinkedIn**: [linkedin.com/in/joaquincardenas-data](https://linkedin.com/in/joaquincardenas-data/)
* **Email**: [Joaquin.data.dev@gmail.com](mailto:Joaquin.data.dev@gmail.com)
