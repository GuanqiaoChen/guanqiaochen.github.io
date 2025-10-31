---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am Guanqiao (Gabriel) Chen, a Computer Science student at New York University, expecting to graduate in 2026 with a Bachelor of Science degree. I have been honored with the Dean's List for 2024 and 2025. My coursework includes Data Structures, Algorithms, Machine Learning, Deep Learning, Software Engineering (Agile), Database Systems, Computer Networking, Object-Oriented Programming, Operating Systems, Optimization, and Stochastic Process.

I am passionate about building scalable distributed systems, agentic AI, and machine learning. My experience spans software engineering internships at major companies including HSBC and Johnson & Johnson, where I worked on AI automation platforms and agentic systems.


# 🔥 News
- *2025.08*: &nbsp;🎉 Completed Software Engineer Internship at HSBC, building Google ADK multi-agent systems and saving ~$420K in costs
- *2025.05*: &nbsp;🎉 Completed Research Assistant position in Reinforcement Learning at NYU
- *2025.01*: &nbsp;🎉 Started working on Distributed Key-Value Storage System project
- *2024.08*: &nbsp;🎉 Completed Software Engineer Internship at Johnson & Johnson, building AI agents with RAG systems
- *2024.09*: &nbsp;🎉 Started Cloud-Native GoPaaS Platform Development project
- *2024.05*: &nbsp;🎉 Awarded Dean's List for 2024
- *2023.08*: &nbsp;🎉 Completed Data Engineer Internship at Deloitte

# 📖 Education

- *2022 - Expected 2026*, **Bachelor of Science in Computer Science**, New York University
  - Awards: 2024, 2025 Dean's List
  - Relevant Coursework: Data Structures, Algorithms, Machine Learning, Deep Learning, Software Engineering (Agile), Database Systems, Computer Networking, Object-Oriented Programming, Operating Systems, Optimization, Stochastic Process

# 💻 Work Experience

## HSBC
**Software Engineer Intern | AI in Automation Tech & Digital Business Services** | *June 2025 - Aug 2025*
- Designed a Google ADK multi-agent system on internal RPA platform; retired 10 legacy apps, saving ~$420K (RTB + SSE) costs.
- Applied Reinforcement Learning loop (evaluate, refine, compose) to turn customer prompts into BPMN workflows and UI pages.
- Exposed Jira, Confluence, and CR as ADK tools with idempotency, RBAC, OAuth2 SA, circuit-breakers, and audit logs.
- Implemented RAG with PGVector + BM25 hybrid search, schema-aware chunking, and Pydantic-typed outputs.
- Added Redis caching for embeddings, top-k retrieval, and responses using TTL and key hashing.

## Johnson & Johnson
**Software Engineer Intern | AI in Digital and Automation Solutions** | *May 2024 - Aug 2024*
- Built an internal AI agent with LangChain, FastAPI, WebSockets, TTS for knowledge retrieval across digital-twin platform.
- Added Redis with LangChain long-term memory to persist conversation state and keep multi-turn incident workflows coherent.
- Implemented Qdrant-backed RAG combining internal data with web signals, boosting accuracy and cutting hallucinations ~35%.
- Leveraged SerpAPI to aggregate web searches, applying filtering and ranking techniques to prioritize search results.

## Deloitte
**Data Engineer Intern | Data Engineer in Financial Advisory** | *Aug 2023 - Aug 2023*
- Built ETL pipelines in Python (pandas/NumPy) and SQL to clean, standardize, and aggregate large financial & ops datasets.
- Automated data verification with Excel VBA, validating 30+ datasets and achieving 100% accuracy.
- Designed star schemas and DAX models in Power BI over SQL views with incremental refresh, delivering drill-down dashboards.

# 🎯 Notable Projects

## Distributed Key-Value Storage System
*Jan 2025 - May 2025*
- Designed a Multi-Raft system delivering 50K QPS throughput, 10 ms P99 latency, and 99.9% availability with linearizable writes.
- Implemented virtual-node consistent hashing for ~95% balance and dynamic shard rebalancing with <1% performance impact.
- Optimized read performance using ReadIndex and FollowerRead, reducing read latency by ~35%.
- Introduced async apply/commit with batch processing, achieving 2x higher throughput.
- Integrated hybrid storage engine combining RocksDB LSM-tree for persistence and B+ tree for in-memory operations.
- Implementing MVCC with snapshot isolation, achieving 99.99% transaction success rate.

## Cloud-Native GoPaaS Platform Development
*Sep 2024 - Dec 2024*
- Built a cloud-native GoPaaS on Go-Micro v3, Kubernetes, and service mesh with less than 50 ms latency and 99.95% uptime.
- Integrated Istio for secure, observability, and load-balancing; automated deployment and rollback via Helm with 3x release speed.
- Scaled Kubernetes clusters with NGINX Ingress and custom controllers for scheduling/routing, handling +60% in service traffic.
- Implemented API Gateway design patterns to handle service discovery, load balancing, and security.
- Added Hystrix for circuit breaking and rate-limiting algorithms to ensure reliability under high traffic, reducing failures by ~65%.
- Designed distributed microservice using gRPC/protobuf service contracts for low-latency, strongly-typed inter-service RPC.
- Containerized with Docker; tuned resources/connection pools and real-time monitored with Prometheus/Grafana for SLOs.

## Coupon Management System
*Jan 2024 - May 2024*
- Built scalable event-driven microservices with Spring Boot/Spring Cloud, sustaining more than 10K tx/min at 99.9% uptime.
- Implemented Kafka Streams and Avro for engagement tracking with less than 100 ms latency and 99.99% delivery accuracy.
- Designed high-throughput RESTful APIs over HBase with Spring Cache and Hystrix circuit breakers for token/entitlement CRUD.
- Integrated Redis Cluster + Sentinel for distributed caching, cutting backend DB load ~20% and speeding bulk redemptions.
- Tuned HBase with Phoenix and block caching to optimize read/write throughput and reduce disk I/O.
- Coordinated distributed services and failover with ZooKeeper to maintain high system availability.

# 🔬 Research

## New York University
**Research Assistant | Reinforcement Learning** | *Jan 2025 - May 2025*
- Simulated high-dimensional contextual bandit in PyTorch, implementing dynamic pricing with RMLP and semiparametric GLMs.
- Analyzed regret bounds across linear, nonlinear, and parametric regimes, studying dimension d, noise, and exploration trade-offs.

# 🎖 Honors and Awards
- *2025*: Dean's List, New York University
- *2024*: Dean's List, New York University

# 💻 Technical Skills

**Programming Languages:** C/C++, C#, Java, Python, SQL, Go, Ruby, JavaScript, TypeScript, Groovy

**Backend Technologies:** Node.js, Express.js, FastAPI, Flask, Spring Boot, Spring Cloud, Spring Security, Rails, Maven, JUnit, Mockito, Swagger (OpenAPI), Postman, Insomnia, Apache Kafka, RabbitMQ, RocketMQ

**Frontend Technologies:** React.js, Vue.js, HTML/CSS

**Databases:** MySQL, PostgreSQL, MongoDB, Redis, HBase, Elasticsearch

**Cloud & DevOps:** AWS (EC2, S3, Lambda), Azure, GCP, Docker, Kubernetes, Jenkins, CI/CD (pipelines), Git, Linux, Shell scripting, Ansible, Kyverno, Ceph

**Agentic AI & Machine Learning:** Langchain, Langgraph, Google ADK, Spring AI, RAG, MCP, PyTorch, TensorFlow, Scikit-learn, LLMs

**Networking & Systems:** TCP/IP, UDP, DNS, IPv6, NAT64, STP, VPN

**Monitoring & Analytics:** Prometheus, Grafana, gNMI, Zeek, ERSPAN
