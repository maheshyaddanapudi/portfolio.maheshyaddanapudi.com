# MAHESH YADDANAPUDI
## ML Engineering Leader — Agentic AI Platform Architecture, MCP & Retrieval

maheshyaddanapudi@gmail.com | [LinkedIn](https://www.linkedin.com/in/maheshyaddanapudi/) | [GitHub](https://github.com/maheshyaddanapudi) | [Medium](https://zzzmahesh.medium.com/)

---

## PROFESSIONAL SUMMARY

Machine learning engineering leader with 17+ years of production engineering experience, focused on architecting agentic AI platforms: multi-agent orchestration, MCP tool gateways and registries, hybrid retrieval (vector, keyword, graph), human-in-the-loop workflows, and agent evaluation/observability. Has designed and built agent platforms end to end — in Python (LangGraph, FastAPI) and Java (Spring AI, Spring Boot) — both inside a large enterprise and in open source, on a foundation of microservices, Kubernetes, and cloud architecture built at Google, Oracle, JPMorgan Chase, and Workday.

---

## PROFESSIONAL EXPERIENCE

### WORKDAY
**Senior Machine Learning Engineer**  
*Sep 2022 - Present | Santa Clara, California, United States*  
*(Software Engineer, Sep 2022 - Feb 2026; Senior ML Engineer since Feb 2026)*

Engineer on an enterprise planning platform, focused on ML-driven forecasting, workflow automation, and agentic AI systems.

- Architected and lead-developed an end-to-end predictive forecasting (ML) application: forecast definitions using historical actuals as reference and a target planned version as output, selectable forecasting models (N-BEATS, Prophet), and dispatch to an ML pipeline that computes forecasts and writes results back to the planned version.
- Built the forecasting scheduler as phase two: create/update and pause/resume schedules, timezone handling, OpenAPI/Swagger documentation, and expanded automated test coverage.
- Designed and led a lightweight, decoupled process/workflow engine powering configurable enterprise workflows — defining its core interfaces, lifecycle operations, and extensibility model.
- Pioneered AI-agent orchestration with the Model Context Protocol (MCP) and Spring AI — server/host integrations exposing enterprise workflow APIs as tools for AI assistants; the host design was adopted as an architectural baseline by the owning team.
- Prototyped natural-language metadata discovery with a hybrid GraphRAG approach — FAISS vector, keyword, and Neo4j graph retrieval fused via reciprocal rank fusion, with LLM intent parsing and grounded synthesis.
- Champion of AI-assisted engineering — applying LLM tooling (Claude, GPT-4, Cursor) to design, prototyping, code/test generation, and debugging, and evangelizing AI-first workflows across the team.

### ORACLE
**Principal Member of Technical Staff**  
*Jan 2022 - Sep 2022 | Seattle, Washington, United States*

Worked as a Principal Member of Technical Staff, contributing to Oracle's cloud infrastructure and enterprise solutions.

### GOOGLE
**Software Engineer**  
*May 2021 - Dec 2021 | Warsaw, Mazowieckie, Poland*

Managed customer problems through effective diagnosis and resolution. Worked on Google Cloud Platform products and collaborated with multiple product and engineering teams.

### JPMORGAN CHASE & CO.
**Software Engineering Lead**  
*Dec 2016 - May 2021 | Hyderabad, Telangana, India*

Served as Software Engineering Lead / Architect for development of an org-wide coding-less Automation Suite for Production Management. Led a team of developers working with technologies like Ansible, Netflix Conductor, Spring Boot, Docker / Kubernetes, and RESTful APIs.

### VIRTUSA POLARIS
**Senior Consultant**  
*Apr 2016 - Dec 2016 | Hyderabad, Telangana, India*

Served as Senior System Consultant and project lead for 10 associates, organized into Application Support, DBA Support, and Server Support teams providing complete end-to-end support for all Alere Apollo Platform applications.

### VALUELABS
**Senior System Analyst - Project Lead**  
*Jan 2014 - Apr 2016 | Malaysia*

Served as Senior System Analyst and project lead for 7 projects, including 5 support projects with regular monitoring and change-request handling.

- WebSphere DataPower Migration Lead — led the migration of services from Xi50 DataPower to the latest Xi52 DataPower appliances.
- Architect / designer for the PDPA project — developed the entire application single-handedly, applying Java object-oriented design principles.

### VERIZON DATA SERVICES INDIA
**Analyst - Systems Development**  
*Jan 2012 - Jan 2014 | Hyderabad, Telangana, India*

Served as Analyst - Systems Development, Secondary Release Lead, and Module Lead.

- Gathered requirements from onsite coordinators and delegated to / worked with the offshore team for successful deliveries.
- Participated effectively in design and implementation discussions; provided production and testing support whenever required.
- Testing, debugging, defect fixing, and performance tuning of the codebase; worked closely with CVS & SVN to avoid merge conflicts and keep the history clean.

### TATA CONSULTANCY SERVICES
**Systems Engineer**  
*Feb 2009 - Dec 2011 | Chennai, Tamil Nadu, India*

Served as Developer and Backup Project Lead for a team of 7 at offshore.

---

## TECHNICAL SKILLS

- **Agentic AI Architecture**: Multi-Agent Orchestration (LangGraph supervisor–worker, DAG sub-agents), Model Context Protocol (MCP) servers/hosts/gateways, Tool & Agent Registries, Spring AI, A2A (Agent-to-Agent), CodeAct, Human-in-the-Loop Workflows, Docker-Sandboxed Tool Execution
- **Retrieval & RAG**: Hybrid Retrieval (FAISS vector + BM25 keyword + Neo4j GraphRAG), Reciprocal Rank Fusion, Embeddings (sentence-transformers), Apache Lucene, Grounded Synthesis, Elasticsearch
- **Agent Evaluation & Observability**: OpenTelemetry, LangSmith, LLM-as-Judge, Run Tracing & Session Replay, Tool-Call Auditing, Quantified Offline Evaluation, Prometheus/Micrometer
- **ML Engineering**: Time-Series Forecasting (N-BEATS, Prophet), ML Pipelines, MLX Fine-Tuning (LoRA/QLoRA), Prompt Engineering, LLM-Assisted Development (Claude, GPT, Cursor)
- **Programming Languages**: Python, Java, TypeScript, JavaScript
- **Frameworks & Libraries**: FastAPI, Spring Boot, React, Angular
- **Cloud Platforms**: Google Cloud Platform, AWS, Oracle Cloud
- **DevOps & CI/CD**: Docker, Kubernetes, Jenkins, Ansible, Infrastructure as Code (IaC)
- **Databases**: PostgreSQL, Oracle, MySQL, Microsoft SQL Server, IBM DB2, PL/SQL, Elasticsearch, Neo4j
- **Microservices**: Netflix OSS Stack, Spring Cloud, REST APIs, Service-Oriented Architecture (SOA)

---

## OPEN SOURCE & SELECTED SYSTEMS

### Agentic AI Platforms
- **Concierge Agent** - Registry-driven multi-agent platform: runtime MCP tool ingestion, tri-layer tool/skill/sub-agent registries, DAG sub-agent workflows with parallel fan-out, human-in-the-loop approvals, hybrid BM25+embedding retrieval (RRF), and OpenTelemetry + LangSmith run tracing (Python, FastAPI, LangGraph, Postgres, React)
- **MAOS (Multi-Agent Orchestration Service)** - Fully configuration-driven multi-agent orchestration with a LangGraph supervisor, MCP tool plane, A2A agent discovery, and an OpenAI-compatible API
- **Javis-LG** - Six-layer LangGraph supervisor–worker system: DB-persisted "living plans" synced with execution, reflection-based quality loop, dynamic worker registry with per-worker MCP servers, OpenAI-compatible API
- **MY-Manus** - Open-source Manus-style AI agent platform built on the CodeAct architecture, with Docker-sandboxed Python execution, MCP tool discovery, and full session replay
- **TestRail MCP Server** - Spring Boot + Spring AI MCP server exposing 101 TestRail operations through 4 Lucene-backed meta-tools, with a local-only credential security model

### Retrieval & Applied AI
- **Trilayer Generic Search** - Plugin-based hybrid retrieval framework fusing FAISS vector, BM25 keyword, and Neo4j graph search via reciprocal rank fusion, with LLM intent parsing, grounded citation-constrained synthesis, and LLM-as-judge evaluation
- **Transcript Intelligence** - LLM-hybrid analytics over 100 B2B meeting transcripts with a five-tool MCP server; quantified evaluation: 97% categorization accuracy vs. hand labels, r=0.94 sentiment validation, churn-ranking sensitivity analysis

### Maven Central / OSS Artifacts
- **Spring Boot Starter For Conductor OSS** - A Spring Boot starter for Conductor OSS with Queue Configuration
- **Conductor Boot** - Spring Boot Wrapper of Netflix Conductor Server with Embedded Security, Database, and Elasticsearch

### Machine Learning Models
- **StarCoder2 3B** - Base and instruction-tuned versions of StarCoder2 3B model
- **Flowable Documentation Models** - Various Llama and Qwen-based models for Flowable documentation
- **Conductor Documentation Model** - Netflix Conductor documentation model based on Llama 3.2

### GitHub Projects
- **conductor-ng-ui** - Angular UI for Conductor Workflows and Workflow Executions management
- **ansible-playbook-generator-ui** - Angular UI for generating Ansible Playbooks
- **conductor-boot** - Spring Boot Wrapper of Netflix Conductor Server
- **ansible-playbook-json2yaml** - Python Flask Wrapper exposing APIs to convert JSON to Ansible Playbook YAML
- **ansible-docs-boot** - Spring Boot Wrapper to Expose Ansible Commands with I/O fields through APIs
- **spring-boot-starter-conductor** - Spring Boot Starter For Netflix Conductor Community Version

---

## EDUCATION

### ANNA UNIVERSITY
**Bachelor of Engineering in Computer Science**  
*2004 - 2008*

---

## CERTIFICATIONS

- AI Agentic Framework Using Spring AI - Vanderbilt University *(In Progress)*
- Team Software Development with Generative AI - DeepLearning.AI (2025)
- Generative AI for Software Development - DeepLearning.AI (2025)
- Jenkins, From Zero To Hero: Become a DevOps Jenkins Master - Udemy (2020)
- The Complete Agile Scrum Fundamentals Course - Udemy (2020)
- Spring Boot Microservices and Spring Cloud - Udemy (2020)
- Mastering Ansible - Udemy (2020)
- IBM Websphere Certified Solutions Developer: Message Broker - IBM (2013)
- IBM Websphere Certified SOA Associate - IBM (2013)
- IBM Websphere Certified Solutions Developer: Web Services Development on Websphere Application Server - IBM (2012)
- IBM Websphere Certified Solutions Developer - Websphere Integration Developer - IBM (2012)

---

## PUBLICATIONS

- **Netflix Conductor — Spring Boot Wrapper** - A comprehensive guide to creating a Spring Boot wrapper for Netflix Conductor Server
- **Bridging Realms: Envisioning a World of Coexistence Between Humans and AI** - Exploration of the parallel evolution of human and artificial intelligence
- **Scientific Proof of God. Possible?** - An exploration of the intersection between science and metaphysics

---

## LANGUAGES

- English (Professional)
- Hindi (Professional)
- Telugu (Native)
