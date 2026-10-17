<h1 align="center">Shibin Biji Thomas</h1>

<p align="center"><b>Software Engineer · AI-Native Backend & Distributed Systems</b></p>

<p align="center">
I build AI-native cloud software — LLM-integrated workflows, event-driven microservices, and the data pipelines and CI/CD gates that keep them reliable in production.
</p>

<p align="center">
Software Engineer Intern @ <b>LinkedIn</b> &nbsp;·&nbsp; ex-Software Engineer @ <b>Accenture</b> (3+ yrs) &nbsp;·&nbsp; M.S. Applied Data Intelligence @ <b>San José State University</b> ('27) &nbsp;·&nbsp; San Francisco Bay Area, CA
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shibin-biji-593228183/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:shibinbiji2@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://shibin-portfolio-steel.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
</p>

---

## What I build

- 🤖 **AI-native workflows** — LLM API integration, prompt design, offline model-evaluation loops, RAG, and MCP tooling wired into real services → *LinkedIn internship, ServiceNow AI API Integration Service, AI Medical Chatbot*
- ⚡ **Event-driven & streaming systems** — Kafka / Flink / Airflow pipelines and async workers tuned for latency and throughput → *AI-Native Workflow Automation Engine, Fleet Telemetry Playground*
- ⚙️ **Backend & cloud platforms** — Java / Python / Go / C++ microservices on PostgreSQL, Cassandra & Redis — containerized on Kubernetes, CI/CD-gated, observable → *Accenture, BookTable*

The pattern across all of them: **measure first, then move the number** — latency, accuracy, availability — with a test or automated gate in front of every release.

---

## Experience

### 💼 Software Engineer Intern — LinkedIn &nbsp;·&nbsp; Sunnyvale, CA &nbsp;·&nbsp; *May 2026 – Aug 2026*
- Built AI-native telemetry workflows and REST integration pipelines in Python on AWS (**SNS → Firehose → S3, Glue, Athena, Lambda**) — **~90% less manual reporting**.
- Worked on AI API integration, prompt design, and offline model-evaluation loops in Python / PyTorch; automated scoring routines lifted prediction accuracy **72% → 85%**.
- Refactored high-throughput Python & C++ query layers and fixed staging bottlenecks — end-to-end latency **120 ms → 85 ms**.
- Integrated multi-model LLM workflows (Claude + AI dev tools) for architecture prototyping and automated prompt engineering — convergence reliability **65% → 87%**.
- Shipped containerized deployments on **Kubernetes** with Git + **Airflow** DAGs, unit tests, and CI/CD verification gates.

### 💼 Software Engineer — Accenture &nbsp;·&nbsp; Pune, India &nbsp;·&nbsp; *Jul 2021 – Dec 2024*
- Architected cloud-native Java microservices with secure coding, unit testing, and code review — platform availability **98.2% → 99.7%**.
- Built workflows, business rules, REST APIs, and integrations in JavaScript, TypeScript, and **ServiceNow GlideScript**.
- Redesigned indexed data models on **PostgreSQL** & **Cassandra** — API response times **450 ms → 280 ms**.
- Led customer triage and root-cause debugging in an Agile team; automated CI/CD with **Jenkins, Docker, Git on GCP**.

---

## Featured projects

### ⚡ AI-Native Workflow Automation & Cloud Stream Engine
*A real-time workflow engine that runs event-driven business rules asynchronously across cloud microservices.*

Custom queue algorithms and business rules on **Apache Flink + Kafka** with tuned memory allocation cut average queuing latency **150 ms → 95 ms**; self-healing services on **Kubernetes** with unit tests and automated CI/CD hold **99.5% reliability** under heavy concurrency.

`Python` `Java` `C++` `Kafka` `Flink` `Kubernetes` `Docker` `REST` `SQL`

### 📊 ServiceNow Platform Analytics & AI API Integration Service
*Platform automation services with an LLM- and MCP-powered workflow layer.*

Migrated legacy workflow schemas to **AWS S3 + PostgreSQL** under strict security controls; distributed query workflows, health checks, and dashboards on **Spark, Airflow, and Trino** with SQL optimizations that sped up analytical retrieval **35%**; endpoints exposed over **REST, gRPC, and GraphQL** (Express) with LLM prompt APIs and **MCP** authoring tools for low-latency automation.

`Java` `Python` `GlideScript` `PostgreSQL` `AWS S3` `Spark` `Airflow` `Trino` `gRPC` `GraphQL` `MCP`

### 🍽️ BookTable — Cloud-Native Restaurant Booking 🏆 *2nd Prize, SJ Hacks*
*Restaurant search, reservations, and real-time availability, end to end.*

Spring Boot microservices over **MongoDB** with secure REST APIs (**OAuth2, JWT, RBAC**) for customers, managers, and admins; React frontend with dashboards, notifications, and Google Maps; CI/CD via GitHub Actions to **AWS (EC2, ALB, Auto Scaling)**.

`Java` `Spring Boot` `React` `MongoDB` `OAuth2 / JWT` `GitHub Actions` `AWS`

### 🚗 Fleet Telemetry Playground
*Query a live vehicle fleet with plain filters — "100 cars ≥ 60 MPH, windows down, AC on".*

A **Go** producer streams synthetic vehicle events to **Kafka**; **Airflow** DAGs compact and index them into **PostgreSQL**; a **React** UI runs dynamic fleet queries with a live **WebSocket** tail, backed by a 5-minute **Redis** rolling cache and z-score anomaly flags. Fully Dockerized with GitHub Actions CI.

`Go` `Kafka` `Airflow` `PostgreSQL` `Redis` `React` `WebSocket` `Docker`

---

## Also built

| Project | What it is | Stack |
|---|---|---|
| **AI Medical Chatbot (RAG)** | Retrieval-augmented chatbot that finds and summarizes medical documents in real time — **91% semantic retrieval accuracy** over 5K+ healthcare records | Python · HuggingFace · FAISS · LangChain · Mistral 7B · Streamlit |
| **Spotify Data Warehouse** | End-to-end warehouse on Spotify API data; star schema in Snowflake improved genre / artist query efficiency **30%**; 20+ visualizations | Python · AWS S3 / Glue · Snowflake · Power BI |
| **Real-time Yelp Sentiment** | Streaming ingest → PySpark sentiment classification → S3 history → live Streamlit trend dashboard | Python · Apache NiFi · PySpark · VADER / TextBlob · AWS S3 |

---

## Open source

Contributor to **[rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server)** (⭐ 17.8k) — an AI pipeline engine with a multithreaded C++17 core and 130+ Python-extensible nodes across 15+ LLM providers:

- Core runtime and execution optimizations in the C++17 / Python engine
- **Exactly-once delivery** semantics for event queues
- Integrated **Model Context Protocol (MCP)** authoring tools to automate prompt design and agent-workflow creation

---

## Stack

| Area | Tools I reach for |
|---|---|
| **Languages** | Python · Java · JavaScript / TypeScript · C++17 · Go · SQL · GlideScript · Bash |
| **AI / LLM** | Claude / Claude Code · Model Context Protocol (MCP) · RAG · vLLM · PyTorch · HuggingFace · FAISS · LangChain / LangGraph · Cursor · Windsurf |
| **Backend & APIs** | REST · gRPC / Protobuf · GraphQL · Spring Boot · Node.js / Express · FastAPI · Flask |
| **Data & storage** | PostgreSQL · MySQL · Cassandra · Redis · MongoDB · AWS S3 · Apache Iceberg · PgBouncer · Snowflake |
| **Streaming & processing** | Apache Kafka · Apache Flink · Apache Spark · Trino · Apache Airflow |
| **Cloud & infra** | AWS (Lambda, Firehose, SNS, S3, Glue, Athena, EC2) · GCP · Kubernetes · Helm · Docker |
| **DevOps & tooling** | Git · GitHub Actions · Jenkins · CMake · Linux / systemd · Postman · JUnit · PyTest |

---

## Now

- 🎓 **M.S. Applied Data Intelligence** @ San José State University · graduating **May 2027** — Operating Systems, Distributed Systems, Advanced Algorithms, Database Management, Cloud Infrastructure
- 🔭 **Recently shipped:** AI-native telemetry pipelines and LLM evaluation loops during my **LinkedIn** internship, plus runtime and MCP work on RocketRide
- 🧭 **Exploring next:** agentic workflows on MCP, LLM serving with vLLM, and lakehouse patterns on Iceberg + Trino

---

## Contact

📫 **shibinbiji2@gmail.com** &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/shibin-biji-593228183/) &nbsp;·&nbsp; [Portfolio](https://shibin-portfolio-steel.vercel.app/) &nbsp;·&nbsp; San Francisco Bay Area, CA

**Open to Software Engineering and AI / Backend Engineering roles — New Grad 2027.**
