# Hi there 👋, I'm Trung!

I have a strong interest in building scalable distributed system and backend microservices, currently still exploring and learning every day to broaden my horizons in this domain. My work spans Java/Spring Boot microservices, Kafka streaming, and full-stack applications with React and Node.js. My GitHub repos bring together my ideas, ongoing explorations, along with application projects, focused engineering labs, and documented hands-on experiments that make system behavior easier to understand.

[Featured work](#featured-work) · [Engineering toolkit](#engineering-toolkit) · [Continual Explorations](#continual-explorations)

## What I worked on

- **Service reliability:** service discovery, load balancing, circuit breakers, and workflow retries.
- **Data movement and processing:** MySQL change data capture, Kafka Streams joins, stateful aggregations, and batch processing.
- **Concurrency and Data Reconciliation:** pessimistic/optimistic locking, transaction retries, and Java multithreading.
- **System Observability:** instrumenting APIs and examining request rates, errors, and latency through OpenTelemetry, Prometheus, and Grafana.

## Featured work

| Project | What to look at |
| --- | --- |
| **[Spring REST engineering lab](https://github.com/TrungTVo/spring-rest-boilerplate)** | REST APIs with DTOs, exception handling, OpenAPI, and Actuator. Explore [cursor pagination](https://github.com/TrungTVo/spring-rest-boilerplate/tree/cursor-pagination), [JPA relationships](https://github.com/TrungTVo/spring-rest-boilerplate/tree/entity-relationship), [optimistic locking](https://github.com/TrungTVo/spring-rest-boilerplate/tree/optimistic-lock), [pessimistic locking](https://github.com/TrungTVo/spring-rest-boilerplate/tree/pessimistic-lock) and [transaction retries](https://github.com/TrungTVo/spring-rest-boilerplate/tree/transaction-retries). |
| **[Spring microservices](https://github.com/TrungTVo/spring-microservices)** | Order, payment, and notification service demos using Spring Cloud, Consul discovery, and load-balanced reactive WebClient calls. The [circuit-breaker branch](https://github.com/TrungTVo/spring-microservices/tree/circuit-breaker) adds Resilience4j, simulated failures, and fallback behavior. |
| **[Kafka CDC](https://github.com/TrungTVo/kafka-connect) & [stream processing](https://github.com/TrungTVo/kafka-streams)** | Two complementary labs: MySQL-to-Kafka change data capture with Debezium and connector transformations; Kafka Streams examples covering Avro, Schema Registry, stream joins, KTable enrichment, state stores, aggregations, and windows, etc.. |
| **[API observability stack](https://github.com/TrungTVo/observability-explore/tree/grafana)** | Instrument a Node.js/Express API, route metrics through an OpenTelemetry Collector, and visualize them with Prometheus and a provisioned Grafana dashboard. Includes traffic generation and recording rules for request rate, error ratio, and P95 latency. |
| **[Redis & MongoDB labs](https://github.com/TrungTVo/redis-sample)** | Cache-aside reads with expiration, Pub/Sub, Redis Streams, and contrasting inventory race-condition and locking demonstrations. Includes scripts for exercising concurrent requests. |
| **[Smart Money](https://github.com/TrungTVo/Smart-Money)** | A full-stack personal finance application for tracking accounts and daily transactions, with spending visualizations and authentication. Built with React, Redux, Node.js/Express, MongoDB, Passport, and JWT. |

Several repositories organize independent examples into branches; the links above take you directly to the relevant implementations.

## Engineering toolkit

| Area | Technologies used across my projects and labs |
| --- | --- |
| Languages | Java, TypeScript, JavaScript, Python, SQL |
| Backend & APIs | Spring Boot, Spring Data JPA/Hibernate, Spring Cloud, WebClient, Resilience4j, Node.js, Express |
| Streaming & orchestration | Kafka, Kafka Streams, Kafka Connect, Debezium, Avro, Schema Registry, Temporal |
| Storage & processing | MySQL, MongoDB, Redis, Elasticsearch, Apache Flink, Apache Spark, Hadoop/HDFS, Airflow |
| Observability & tooling | OpenTelemetry, Prometheus, Grafana, Logstash, Kibana, Docker, Docker Compose, Gradle, Maven |
| Frontend & AI exploration | React, Redux, Socket.IO, LangChain, FAISS, n8n |

## Continual Explorations

<details>
<summary><strong>Backend, concurrency & workflows</strong></summary>

- [Spring Boot + Kafka](https://github.com/TrungTVo/springboot-kafka-confluent) — Produce messages, inspect consumer groups and partition assignments, and control listener lifecycles through HTTP endpoints.
- [Temporal Java](https://github.com/TrungTVo/temporal-java) — Exploration on durable execution in distributed transaction. Workflow/activity basics and retries, with branches for [asynchronous execution](https://github.com/TrungTVo/temporal-java/tree/asynchronous-workflow), [queries](https://github.com/TrungTVo/temporal-java/tree/query-message), and [signals](https://github.com/TrungTVo/temporal-java/tree/signal-message).
- [Java concurrency](https://github.com/TrungTVo/threads) — Executors, CompletableFuture, synchronization, locks, latches, deadlocks, and concurrent collections.
- [SQL pagination visualizer](https://github.com/TrungTVo/sql-pagination) — An interactive illustration of offset and cursor pagination with SQL and API examples.
- [Socket.IO chat](https://github.com/TrungTVo/multiusers-chat-socket.io) — A multiuser chat demo with join/leave notifications.

</details>

<details>
<summary><strong>Data processing & local infrastructure</strong></summary>

- [Flink](https://github.com/TrungTVo/flink-explore) — DataStream file processing and Docker configurations for session and application modes.
- [Spark](https://github.com/TrungTVo/spark-explore) — A standalone Spark setup and PySpark sales aggregations reading from HDFS.
- [Hadoop](https://github.com/TrungTVo/hadoop-pseudo-distributed) — A containerized, single-node Hadoop environment with HDFS and YARN configuration.
- [Airflow](https://github.com/TrungTVo/airflow-explore) — DAG examples, local setup, and a custom HTTP GET operator.
- [Multipass notes](https://github.com/TrungTVo/multipass-ubuntu-vm) — Ubuntu VM provisioning and SSH setup.

</details>

<details>
<summary><strong>Monitoring, search & AI experiments</strong></summary>

- [Prometheus](https://github.com/TrungTVo/prometheus-explore) — API metrics, simulated latency and failures, traffic generation, and PromQL examples.
- [Elasticsearch & Kibana](https://github.com/TrungTVo/elk-elasticsearch-sample) — Container setup, log ingestion configurations, and search examples.
- [Logstash](https://github.com/TrungTVo/elk-logstash-sample) — Pipeline configuration and local execution examples.
- [RAG with Python & n8n](https://github.com/TrungTVo/rag-explore-n8n) — YouTube transcript retrieval experiments using chunking, embeddings, FAISS, and an LLM, alongside an n8n workflow.
- [Scene recognition](https://github.com/TrungTVo/spatial-pyramid-matching-scene-recognition) — An earlier computer vision project exploring visual features, classification, and spatial pyramid matching.

</details>

<details>
<summary><strong>Coursework & reference forks</strong></summary>

- [LangChain foundations](https://github.com/TrungTVo/lca-lc-foundations) — Fork of LangChain Academy's course repository for exploring models, tools, memory, MCP, and agent workflows.
- [Spring Batch example](https://github.com/TrungTVo/spring-batch-example-1) — Fork of Tech Primers' CSV-to-database example.

</details>

---

**Engineering interests:** backend microservices, distributed systems, streaming platforms, and developer tooling.

[Browse my repositories](https://github.com/TrungTVo?tab=repositories)
