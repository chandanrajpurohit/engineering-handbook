# Engineering Handbook 📚

A comprehensive, curated, and modular engineering documentation repository covering core technologies across distributed systems, cloud computing, data engineering, backend, frontend, mobile, security, observability, AI, and developer tools.

---

## 🗂️ Repository Structure

```text
engineering-handbook/
│
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── CODE_OF_CONDUCT.md
│
├── docs/
│   ├── messaging/
│   │   ├── kafka/
│   │   └── rabbitmq/
│   ├── data-engineering/
│   │   ├── airflow/
│   │   ├── spark/
│   │   └── flink/
│   ├── cloud/
│   │   ├── aws/
│   │   ├── azure/
│   │   └── gcp/
│   ├── containers/
│   │   ├── docker/
│   │   └── kubernetes/
│   ├── infrastructure/
│   │   ├── terraform/
│   │   └── ansible/
│   ├── ci-cd/
│   │   └── jenkins/
│   ├── programming/
│   │   ├── python/
│   │   ├── java/
│   │   └── javascript/
│   ├── backend/
│   │   ├── django/
│   │   ├── nodejs/
│   │   └── spring-boot/
│   ├── frontend/
│   │   ├── react/
│   │   └── angular/
│   ├── mobile/
│   │   ├── react-native/
│   │   └── android/
│   ├── databases/
│   │   ├── postgresql/
│   │   ├── mongodb/
│   │   └── sql-server/
│   ├── bi-integration/
│   │   ├── ssis/
│   │   └── power-bi/
│   ├── security/
│   │   ├── keycloak/
│   │   ├── oidc/
│   │   └── jwt/
│   ├── observability/
│   │   ├── prometheus/
│   │   ├── grafana/
│   │   ├── loki/
│   │   └── appdynamics/
│   ├── api-management/
│   │   ├── kong/
│   │   ├── rest/
│   │   └── soap/
│   ├── collaboration/
│   │   ├── jira/
│   │   └── confluence/
│   └── ai/
│       ├── langchain/
│       └── langgraph/
│
└── resources/
    ├── architecture/
    ├── cheat-sheets/
    ├── interview-questions/
    └── roadmaps/
```

---

## 📖 Documentation Index

### ⚡ [Messaging & Event Streaming](docs/messaging/README.md)
- [Apache Kafka](docs/messaging/kafka/README.md) - Distributed event streaming, topic partitioning, consumer groups, and stream processing.
- [RabbitMQ](docs/messaging/rabbitmq/README.md) - AMQP message broker, direct/fanout/topic exchanges, and quorum queues.

### 🔄 [Data Engineering & Big Data](docs/data-engineering/README.md)
- [Apache Airflow](docs/data-engineering/airflow/README.md) - Workflow orchestration, DAG design, custom operators, and sensors.
- [Apache Spark](docs/data-engineering/spark/README.md) - Distributed batch & stream processing, DataFrames, and Catalyst optimizer.
- [Apache Flink](docs/data-engineering/flink/README.md) - Stateful computations over unbounded and bounded data streams, event-time processing.

### ☁️ [Cloud Computing](docs/cloud/README.md)
- [Amazon Web Services (AWS)](docs/cloud/aws/README.md) - EC2, S3, RDS, Lambda, IAM, VPC, and AWS architectural best practices.
- [Microsoft Azure](docs/cloud/azure/README.md) - Virtual Machines, AKS, Azure SQL, Entra ID, and cloud governance.
- [Google Cloud Platform (GCP)](docs/cloud/gcp/README.md) - Compute Engine, GKE, BigQuery, Pub/Sub, and Cloud Run.

### 📦 [Containers & Orchestration](docs/containers/README.md)
- [Docker](docs/containers/docker/README.md) - Containerization, multi-stage Dockerfiles, caching, and Docker Compose.
- [Kubernetes (K8s)](docs/containers/kubernetes/README.md) - Pods, Deployments, Services, Ingress, StatefulSets, and Helm charts.

### 🏗️ [Infrastructure as Code & Automation](docs/infrastructure/README.md)
- [HashiCorp Terraform](docs/infrastructure/terraform/README.md) - Declarative IaC, modules, state management, and remote backends.
- [Ansible](docs/infrastructure/ansible/README.md) - Agentless automation, playbooks, roles, idempotency, and Ansible Vault.

### 🚀 [CI/CD & DevOps](docs/ci-cd/README.md)
- [Jenkins](docs/ci-cd/jenkins/README.md) - Automation server, Jenkinsfile pipelines, distributed agents, and CI/CD pipelines.

### 💻 [Programming Languages](docs/programming/README.md)
- [Python](docs/programming/python/README.md) - Idiomatic Python, OOP, asyncio, packaging, and concurrency.
- [Java](docs/programming/java/README.md) - JVM architecture, memory management, garbage collection, and modern Java features.
- [JavaScript / TypeScript](docs/programming/javascript/README.md) - Event loop, async/await, closures, TypeScript typing, and DOM/Node APIs.

### ⚙️ [Backend Engineering](docs/backend/README.md)
- [Django & DRF](docs/backend/django/README.md) - MVT framework, ORM optimization, REST framework serializers, and auth.
- [Node.js](docs/backend/nodejs/README.md) - Event-driven runtime, Express, Fastify, async streams, and performance profiling.
- [Spring Boot](docs/backend/spring-boot/README.md) - IoC, Spring Data JPA, Spring Security, microservices, and Actuator.

### 🎨 [Frontend Development](docs/frontend/README.md)
- [React](docs/frontend/react/README.md) - Component lifecycle, modern hooks, state management, and Next.js / React Server Components.
- [Angular](docs/frontend/angular/README.md) - Component-driven architecture, RxJS, Dependency Injection, and Angular Signals.

### 📱 [Mobile Development](docs/mobile/README.md)
- [React Native](docs/mobile/react-native/README.md) - Cross-platform mobile development, native bridges, and React architecture.
- [Native Android](docs/mobile/android/README.md) - Modern Android app development with Kotlin, Jetpack Compose, and Android architecture components.

### 🗄️ [Databases & Storage](docs/databases/README.md)
- [PostgreSQL](docs/databases/postgresql/README.md) - ACID compliance, advanced indexing (B-Tree, GIN, GiST), JSONB, and MVCC.
- [MongoDB](docs/databases/mongodb/README.md) - NoSQL document store, aggregation framework, replica sets, and sharding.
- [Microsoft SQL Server](docs/databases/sql-server/README.md) - T-SQL, query execution plans, Always On availability groups, and indexing.

### 📊 [BI & Data Integration](docs/bi-integration/README.md)
- [SQL Server Integration Services (SSIS)](docs/bi-integration/ssis/README.md) - Enterprise ETL pipelines, data transformations, and SSISDB catalog.
- [Microsoft Power BI](docs/bi-integration/power-bi/README.md) - Interactive reporting, DAX calculations, Power Query (M), and data modeling.

### 🔐 [Identity, Authentication & Security](docs/security/README.md)
- [Keycloak](docs/security/keycloak/README.md) - Open source IAM, SSO, realms, clients, user federation, and API security.
- [OpenID Connect (OIDC)](docs/security/oidc/README.md) - Identity layer on OAuth 2.0, Authorization Code Flow with PKCE, and token claims.
- [JSON Web Tokens (JWT)](docs/security/jwt/README.md) - Token structure, cryptographic signatures, security vulnerabilities, and validation.

### 📈 [Observability & Monitoring](docs/observability/README.md)
- [Prometheus](docs/observability/prometheus/README.md) - Time-series metrics, PromQL, exporters, and Alertmanager.
- [Grafana](docs/observability/grafana/README.md) - Visual dashboards, multi-source observability, templating, and alerting.
- [Grafana Loki](docs/observability/loki/README.md) - Scalable log aggregation, LogQL, Promtail, and correlated telemetry.
- [AppDynamics](docs/observability/appdynamics/README.md) - Enterprise APM, transaction flow maps, diagnostic snapshots, and health rules.

### 🌐 [API Management & Integration](docs/api-management/README.md)
- [Kong API Gateway](docs/api-management/kong/README.md) - Cloud-native gateway, plugins, rate limiting, and Kubernetes Ingress.
- [REST & API Design](docs/api-management/rest/README.md) - REST principles, HTTP semantics, versioning, status codes, and OpenAPI specifications.
- [SOAP](docs/api-management/soap/README.md) - XML-based messaging protocol, WSDL contracts, WS-Security, and enterprise web services.

### 👥 [Project Management & Collaboration](docs/collaboration/README.md)
- [Jira Software](docs/collaboration/jira/README.md) - Agile project management, Kanban/Scrum boards, JQL filters, and automation rules.
- [Confluence](docs/collaboration/confluence/README.md) - Collaborative workspace, technical specifications, knowledge base, and team documentation.

### 🤖 [AI & Agent Frameworks](docs/ai/README.md)
- [LangChain](docs/ai/langchain/README.md) - LLM application framework, LCEL, prompt templates, RAG, and tool execution.
- [LangGraph](docs/ai/langgraph/README.md) - Cyclic graph-based multi-agent systems, human-in-the-loop, and state persistence.

---

## 🛠️ Resources & Guides

- 🏛️ **[Architecture Blueprints](resources/architecture/README.md)**: Reference system designs, microservices vs monolith, event-driven architectures, and high-availability patterns.
- 📑 **[Cheat Sheets](resources/cheat-sheets/README.md)**: Quick-reference cards for Git, Docker, Kubernetes, Linux, SQL, and regular expressions.
- 🎯 **[Interview Questions](resources/interview-questions/README.md)**: Curated system design, data engineering, backend, and DevOps interview questions with answers.
- 🗺️ **[Roadmaps](resources/roadmaps/README.md)**: Learning paths and skill progressions for Full Stack, Data Engineering, DevOps, and AI.

---

## 🤝 Contributing

Contributions, corrections, and additions are welcome! Please check out [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
