<h1 align="center">Shibin Biji Thomas</h1>

<p align="center"><b>Software Engineer · AI/ML · Full-Stack · Cloud Backend</b></p>

<p align="center">
Hands-on experience in AI/ML, full-stack and cloud backend engineering, from shipping production systems at LinkedIn and Accenture.
</p>

<p align="center">
AI/ML &amp; Software Engineer Intern @ <b>LinkedIn</b> &nbsp;·&nbsp; ex-Software Engineer @ <b>Accenture</b> &nbsp;·&nbsp; M.S. Applied Data Intelligence @ <b>San José State University</b> (Dec 2026) &nbsp;·&nbsp; San Francisco Bay Area, CA
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shibin-biji-593228183/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:shibinbiji2@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://shibin-portfolio-steel.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
</p>

<p align="center"><i>Open to new-grad Software Engineering roles · MS graduating December 2026</i></p>

---

## About me

- 🤖 At **LinkedIn** I worked on the **feed recommendation system**, shipping ranking-model improvements in **PyTorch and TensorFlow** (11 of 12 AUC wins), along with RAG and LLM evaluation pipelines.
- 🧱 Before that I spent **three and a half years at Accenture** as a **full-stack engineer**, building React and TypeScript apps on Go, Java and Python microservices on AWS, and raising platform availability from **98.2% to 99.7%**.
- 🌐 I contribute to **[rocketride-server](https://github.com/rocketride-org/rocketride-server)**, a ⭐ 17.8k open-source C++/Python AI pipeline engine, fixing bugs in its CLI, LLM provider integrations, and database and graph nodes.

---

## Experience

### 💼 AI/ML &amp; Software Engineer Intern — LinkedIn &nbsp;·&nbsp; Sunnyvale, CA &nbsp;·&nbsp; *May 2026 – Aug 2026*
- Delivered production **ranking-model optimizations for the feed recommendation system** in **PyTorch and TensorFlow** across concurrent pipelines: **11/12 AUC wins** (up to +0.20% Click) and 11/12 Normalized Entropy (NE) improvements.
- Built custom **RAG pipelines, LLM evaluation workflows and AI agent frameworks** in Python and PyTorch, using vector databases to raise prediction accuracy from **72% to 85%**.
- Engineered automated cloud telemetry, workflow automation and audit monitoring pipelines on AWS (**SNS → Firehose → S3, Lambda**) and GCP in Go and Python, cutting manual reporting effort by **90%**.
- Developed high-throughput serverless microservices and backend APIs in Go and Python, optimizing stream processing and event feedback loops to cut latency from **120 ms to 85 ms**.
- Used AI tools (Claude, Copilot) and serverless AWS Lambda routines for rapid service prototyping, raising execution reliability from **65% to 87%**.
- Ran containerized services on **AWS EKS and Kubernetes** with Docker, Airflow DAGs and Git, with automated unit tests and CI/CD verification gates.

### 💼 Software Engineer (Full-Stack) — Accenture &nbsp;·&nbsp; Pune, India &nbsp;·&nbsp; *Jul 2021 – Dec 2024*
- Architected scalable serverless microservices and backend transaction systems in **Go, Java and Python**, lifting platform availability from **98.2% to 99.7%**.
- Built client web apps and integrations in **React.js, TypeScript** and REST APIs, and designed **gRPC** contracts and **GraphQL** schemas with Protobuf to standardize data flow.
- Tuned **PostgreSQL** schemas, indexes, queries and connection pooling, cutting backend API response times from **450 ms to 280 ms**.
- Automated deployments with **Docker, Kubernetes and Jenkins on AWS and GCP**, with live telemetry monitoring and automated tests for zero-downtime releases.

---

## Open source

Contributor to **[rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server)** (⭐ 17.8k), an open-source, multithreaded C++17/Python engine that runs AI workflows across 130+ Python nodes, 15+ LLM providers and databases.

| PR | What it fixes | Status |
|---|---|---|
| [#2679](https://github.com/rocketride-org/rocketride-server/pull/2679) | A bare `--modelserver` port (e.g. `--modelserver=5590`) was read as a hostname; it now means `localhost:PORT`. Passed CI on macOS, Ubuntu and Windows | ✅ Merged |
| [#2680](https://github.com/rocketride-org/rocketride-server/pull/2680) | The Gemini LLM node now actually sends the configured output-token limit to Google and saves it where it is read back; image models capped at Google's published limits | 🔍 In review |
| [#3276](https://github.com/rocketride-org/rocketride-server/pull/3276) | With the graph `execute` tool disabled, agents now get pointed to the read tools (`get_data`, `query`) instead of a dead-end error. Covers FalkorDB, Neo4j and RocketRide Graph | 🔍 In review |
| [#3277](https://github.com/rocketride-org/rocketride-server/pull/3277) | An unfilled `${ROCKETRIDE_*}` credential in a database or graph node now stops the run and names the missing variable, across 7 database and graph nodes; 19 new tests | 🔍 In review |

---

## Featured projects

### 🩹 [Mender — AI CI-Failure Diagnosis GitHub App](https://github.com/Shibin506/mender)
*A GitHub App that reads a failed CI run on a pull request and posts the root cause and a fix.*

<a href="https://github.com/Shibin506/mender"><img src="https://github.com/Shibin506/mender/raw/main/docs/images/demo.gif" alt="Mender demo: a failing test is diagnosed, the fix is verified, and the tests go green" width="720"/></a>

- Diagnoses failures with an LLM (**Claude or Gemini**, typed structured output) and shows a fix only if it applies to the PR's head commit; locally it also runs the tests on the patched code and hides fixes that still fail.
- Broker-less **Postgres job queue** (`SKIP LOCKED`) with webhook signature checks, deduplication, retries with backoff and crashed-job recovery; a concurrency test shows exactly-once claiming across 8 workers.
- Log extractor covering ~30 failure patterns across 8 toolchains sends **~0.3% of each log** to the model; on a 30-case eval, Gemini 3.5 Flash got the failure type right in **25 of 26** answered cases and named the file to fix in **17 of 19**.

`Python` `FastAPI` `PostgreSQL` `Claude API` `Gemini API` `GitHub Apps` `SQLAlchemy` `Docker` `Prometheus` `GitHub Actions`

### 🏋️ [Spotter — Real-Time AI Form Coach](https://github.com/Shibin506/Spotter) &nbsp;·&nbsp; [**Try it live ↗**](https://spotter-gray.vercel.app)
*Prop your phone up side-on and lift: it counts reps, checks every one, and tells you what to fix, live.*

<a href="https://spotter-gray.vercel.app"><img src="https://github.com/Shibin506/Spotter/raw/main/docs/images/live.png" alt="Spotter live view: rep count, joint angle and skeleton over the video, with feedback on the last rep (sample run on a drawn test mannequin)" width="720"/></a>

- Runs entirely in the browser: **MediaPipe** pose tracking on the phone's GPU feeds a **TypeScript** analyzer that **recognises 6 exercises from the first rep**, checks every rep (depth, lockout, knees caving in, hips rising first) and **speaks the fix** as the rep ends. The video never leaves the device.
- **Bar speed in m/s from the camera alone**: says when to stop once speed drops 20% (with a reps-left estimate) and estimates a **1-rep max** from a load-velocity fit. Makes a **shareable highlight clip** with a slow-motion freeze on the rep worth a second look; hands-free voice commands; an **AI coach note from a Llama model on Groq**, via a serverless API that sends only the set's numbers (never video).
- A labelling page, an accuracy eval (rep recall/precision, per-flag F1) and a **PyTorch → ONNX** training pipeline for a learned form model; **68 unit tests** plus **Playwright** tests running the real model in headless Chromium.

`TypeScript` `React` `MediaPipe` `Computer Vision` `PyTorch` `ONNX` `Groq (Llama)` `Serverless` `WebAssembly` `PWA` `Playwright` `Vercel`

### 📝 [Minutes — AI Meeting Copilot](https://github.com/Shibin506/minutes-ai)
*Upload a meeting transcript, get decisions and action items linked to the exact timestamp, then ask questions across all meetings.*

<a href="https://youtu.be/X2rIOmC_pgo"><img src="https://github.com/Shibin506/minutes-ai/raw/main/docs/images/demo-video.png" alt="Watch the 1:45 narrated Minutes demo on YouTube" width="720"/></a>

▶️ **[Watch the 1:45 narrated demo on YouTube](https://youtu.be/X2rIOmC_pgo)**

- Summary, decisions and action items each link to the transcript timestamp; the model cites segment numbers, so timestamps cannot drift.
- Streamed answers (server-sent events) with numbered citations, retrieved from an **SQLite FTS5 BM25** index; retrieval scores **hit@3 = 1.00** on a 20-question eval that runs in CI.

`Python` `FastAPI` `SQLite FTS5` `Claude API` `Gemini API` `React` `TypeScript` `Docker` `GitHub Actions`

### 🔦 [Lumen — RAG Analytics & Client Integration Platform](https://github.com/Shibin506/rag-analytics-platform)
*Client apps stream events and documents in; a lake pipeline makes them fast to query; an assistant answers from the documents with citations.*

- A **Go** gateway ingests events over **gRPC and REST** with per-tenant JSON Schema validation (~78K events/s from one client) into an **S3** data lake; a **Java GraphQL** API versions schemas and rejects breaking changes.
- A nightly **Airflow** pipeline runs **Spark** compaction to partitioned Parquet and **Trino** rollups with row-count reconciliation, cutting dashboard query latency by **70%** over 2.35M events.
- RAG assistant with hybrid **pgvector** + full-text retrieval, cited streaming answers and feedback-aware ranking (**0.89 hit@3** on a 26-question eval), plus a **React + TypeScript** dashboard.

`Go` `Java` `Python` `TypeScript` `React` `GraphQL` `gRPC` `Spark` `Trino` `Airflow` `PostgreSQL` `pgvector` `S3` `Docker`

### 🗄️ [StrataKV — Crash-Safe Storage Engine in Rust](https://github.com/Shibin506/StrataKV)
*A log-structured merge tree, the design behind LevelDB, RocksDB and Cassandra.*

- Checksummed write-ahead log, SSTables with Bloom filters and block index, levelled background compaction, and **MVCC snapshots** with range scans that stay consistent while writers and compaction run.
- Crash tests kill a real process at every step of every disk operation.
- On 1M keys: level with **RocksDB** on random writes (381K vs 386K ops/s) and **1.6x faster** on in-memory point reads.

`Rust` `LSM Tree` `Write-Ahead Log` `MVCC` `Bloom Filters` `Criterion`

---

## More projects

| Project | What it is | Stack |
|---|---|---|
| **[redos-proof](https://github.com/Shibin506/redos-proof)** | Finds regexes vulnerable to catastrophic backtracking (ReDoS) in JS / TS / Python / Ruby code and **proves** each finding by running the generated attack on the real engines; **100% recall, 0 false positives** on a self-verifying corpus. CLI, pre-commit hook, GitHub Action and SARIF output | Rust · NFA modelling · Static analysis · SARIF |
| **[MedBridge](https://github.com/Shibin506/MedBridge)** | Turns hospital discharge papers into a plan patients can follow: an LLM extracts medicines, appointments and warning signs, and code verifies every item against the original. Plans in 8 languages, daily SMS / Telegram check-ins that escalate to a care-team dashboard; **804 tests**, incl. a 336-case safety eval | Python · FastAPI · Next.js · TypeScript · LLMs · Twilio · Telegram |
| **[ScreenSensei](https://github.com/Shibin506/ai-desktop)** *(team project, Cal Hacks 13.0)* | Desktop AI tutor that reads your screen, points and draws on it, and talks you through math, chess, software and languages step by step; narration starts **~3 s** after a question while the rest of the lesson streams in. 380+ unit tests and a 13-case accuracy eval | TypeScript · Electron · React · Fastify · Claude · Cartesia · Convex |
| **Autonomous AI Agent & Serverless Workflow Engine** | Agent framework and serverless workflow engine with custom RAG pipelines and Kafka; event-driven streaming in Apache Flink cut real-time queuing latency from **150 ms to 95 ms**, on AWS EKS at 99.5% node reliability | Go · Python · Rust · Kafka · Flink · AWS Lambda · Kubernetes |
| **[BookTable](https://github.com/Shibin506/-BookTable-Cloud-Native-Restaurant-Booking-System)** 🏆 *2nd Prize, SJ Hacks* | Restaurant search, reservations and real-time availability: Spring Boot microservices on MongoDB with OAuth2 / JWT / RBAC, a React frontend, and CI/CD to AWS (EC2, ALB, Auto Scaling) | Java · Spring Boot · React · MongoDB · AWS |
| **[GlobalGuide AI Travel Planner](https://github.com/Shibin506/GlobalGuide-AI-Travel-Planner)** | Agentic travel planner on LangGraph that reasons across **9 custom tools** (weather, places, currency) to build personalized itineraries, served by FastAPI | Python · LangGraph · Groq LLM · FastAPI · Streamlit |
| **[AI Medical Chatbot (RAG)](https://github.com/Shibin506/AI-MEDICAL-CHATBOT-with-RAG)** | RAG chatbot that retrieves and summarizes medical documents in real time; **91% semantic retrieval accuracy** over 5K+ healthcare records | Python · HuggingFace · FAISS · LangChain · Mistral 7B |
| **[Spotify Data Warehouse](https://github.com/Shibin506/Spotifyzer)** | End-to-end warehouse on Spotify API data; a Snowflake star schema made genre / artist queries **30%** faster; 20+ visualizations | Python · AWS S3 / Glue · Snowflake · Power BI |
| **[Real-time Yelp Sentiment](https://github.com/Shibin506/Sentiment-Analysis-on-Yelp-Reviews)** | Streaming ingest with Apache NiFi, PySpark sentiment classification of 5,000+ reviews at 90%+ accuracy, S3 history and a live Streamlit dashboard | Python · NiFi · PySpark · VADER / TextBlob · AWS S3 |

---

## Skills

| Area | Tools |
|---|---|
| **Languages** | Go · Python · TypeScript · JavaScript · Java · C++ · Rust · SQL · Bash |
| **AI / ML** | PyTorch · TensorFlow · Recommendation Systems · Feed Ranking · RAG Pipelines · LLMs · LLM Evaluation · LangChain · Vector Databases · AI Agents |
| **Full-stack & APIs** | React · Next.js · Node.js · REST · gRPC · Protobuf · GraphQL · WebSockets · Microservices |
| **Data & cloud** | PostgreSQL · DynamoDB · Redis · Cassandra · Vector Search · AWS · GCP |
| **Streaming & processing** | Kafka · Apache Flink · Apache Spark · Trino · Airflow · Serverless · Distributed Systems |
| **DevOps & testing** | Docker · Kubernetes · Git · CI/CD · Jenkins · GitHub Actions · PyTest · Linux · System Monitoring |

---

## Education

🎓 **M.S. Applied Data Intelligence**, San José State University · *Jan 2025 – Dec 2026 (expected)* · GPA 3.5
<br/>Coursework: Distributed Systems · Database Management · Algorithms · Cloud Infrastructure · Machine Learning

---

## Contact

📫 **shibinbiji2@gmail.com** &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/shibin-biji-593228183/) &nbsp;·&nbsp; [Portfolio](https://shibin-portfolio-steel.vercel.app/) &nbsp;·&nbsp; San Francisco Bay Area, CA

**Open to new-grad Software Engineering roles (AI/ML, full-stack, backend) · MS graduating December 2026.**
