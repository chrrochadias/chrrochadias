# Christopher Rocha Dias

**Ten years building production systems — now working in data engineering.**

I spent a decade as a backend engineer on systems where being wrong was expensive:
payment integrations, a live data-model migration across ~30 tables with zero downtime,
and a public platform serving 100k+ users.

More recently I've specialised into data engineering — a master's in Data Engineering
& Data Science, a Databricks Data Engineer Associate certification, and the projects
pinned below.

What I bring to data work is the part that's usually missing: production instinct.
Models that survive real volume, pipelines that fail loudly rather than silently,
and migrations that don't take the platform down.

📫 [Mail](mailto:christopher.rochadias@gmail.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/christopher-rocha-dias/)

---

## 🛠️ Tech Stack

**Languages & processing** · Python · PySpark · SQL · Polars
**Databases** · PostgreSQL · MongoDB · pgvector · Redis · FAISS
**Pipelines & orchestration** · dbt · Airbyte · Kestra · Redpanda (Kafka)
**Cloud & deployment** · AWS (RDS, ECS Fargate, ECR, S3, EventBridge, Bedrock, ElastiCache, CloudWatch) · Docker · GitHub Actions
**AI / NLP** · LangChain · Mistral AI · RAG · smolagents · RAGAS

---

## 📂 Data Projects

> Each project addresses a realistic professional brief and is documented with a detailed README (context, architecture, stack, key takeaways).

### 🎟️ P13 — From POC to MVP: an AI-powered cultural recommendation system
Design study to industrialize a RAG chatbot (Puls-Events): scalable cloud architecture, prioritized macro backlog, build/OPEX cost modeling. Stateless architecture on AWS — all state held in managed services (RDS + pgvector, ElastiCache, Bedrock, ECS Fargate), with agentic web search via smolagents.
`Architecture` · `AWS` · `Project management` · `Cost modeling`

### 🏃 P12 — End-to-end sports data pipeline (POC)
Proof of concept for a sports-activity rewards system at Sport Data Solution (fitness analytics start-up): a full pipeline covering extraction, transformation, loading, data-quality testing, and continuous monitoring. Computes the financial impact of employee sports incentives, with Slack notifications and a Power BI report featuring replayable historical indicators.
ELT · Data quality · Monitoring · Power BI · Slack
🔗 [[P12 repo link](https://github.com/chrrochadias/Projet12_Christopher_Rocha_Dias_Sport-Data)]

### 🔍 P11 — Semantic search proof of concept (RAG)
Proof of concept for a retrieval-augmented recommendation engine: LangChain + Mistral + FAISS, fed by the OpenAgenda API and evaluated with RAGAS. Surfaced the limits of RAG (metadata filtering, the *living dataset* problem).
`RAG` · `LangChain` · `Mistral` · `FAISS` · `RAGAS`
🔗 [[P11 repo link](https://github.com/chrrochadias/Projet11_Christopher_Rocha_Dias_Puls-events-rag)]

### ⚙️ P10 — Workflow orchestration with Kestra
Design of an orchestrated pipeline architecture integrating Spark, Redpanda, and PostgreSQL. Study of declarative orchestration and dependency management between tasks.
`Kestra` · `Orchestration` · `Spark` · `PostgreSQL`
🔗 [P10 repo link]

### 📡 P9 — Real-time data processing
Streaming proof of concept with PySpark Structured Streaming and Redpanda in a local Docker environment. Modeling of a hybrid infrastructure for an industrial data use case.
`PySpark` · `Structured Streaming` · `Redpanda` · `Docker`
🔗 [[P9 repo link](https://github.com/chrrochadias/projet9-christopher-rochadias-indutech-poc)]

### 🔄 P8 — Modern cloud ELT pipeline
End-to-end ELT pipeline: Airbyte (ingestion) + PostgreSQL + dbt Core (transformation), deployed on AWS (RDS, ECR, ECS Fargate, EventBridge). Modern Extract-Load-Transform approach with dbt tests and documentation.
`ELT` · `dbt` · `Airbyte` · `AWS` · `PostgreSQL`
🔗 [[P8 repo link](https://github.com/chrrochadias/Projet8_Christopher_Rocha_Dias)]

### 🍃 P7 — NoSQL modeling and querying with MongoDB
Analysis of rental data (Airbnb Paris/Lyon) with MongoDB: ReplicaSet, sharding, aggregation pipelines, Python integration via PyMongo and Polars.
`MongoDB` · `NoSQL` · `Aggregation` · `Sharding`
🔗 [P7 repo link]

---

## 📫 Get in touch

Open to Data Engineering opportunities.
[Mail](mailto:christopher.rochadias@gmail.com) · [LinkedIn](https://www.linkedin.com/in/christopher-rocha-dias/)
