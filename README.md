# Gourav Bansal

**Software Engineer II · Backend Systems · Data Infrastructure · AI Search**

I build backend services and data systems where latency, throughput, and reliability matter. My work spans event-driven microservices, large-scale data pipelines, analytical databases, and retrieval systems that combine vector search with knowledge graphs.

- **Currently:** Software Engineer II at Payoneer
- **Previously:** MakeMyTrip
- **Based in:** Gurugram, India
- **Education:** B.Tech. in Computer Science and Engineering, NIT Delhi

[LinkedIn](https://linkedin.com/in/gouravb20) · [GitHub](https://github.com/gouravb20) · [LeetCode](https://leetcode.com/u/gouravb20)

---

## What I work on

- **Backend engineering:** Java, Spring Boot, C#, ASP.NET, REST, gRPC, microservices
- **Streaming and data pipelines:** Apache Beam, Google Cloud Dataflow, Kafka, Pub/Sub, Parquet
- **Databases and retrieval:** Bigtable, ClickHouse, Aerospike, Neo4j, Qdrant
- **Cloud and delivery:** GCP, AWS, Docker, Kubernetes, Helm, Argo CD
- **AI-powered search:** Vector similarity search, knowledge graphs, semantic retrieval, embeddings

## Selected engineering work

### Data Pipelines Topology Redesign
At Payoneer, I built Apache Beam pipelines on Google Cloud Dataflow to join, validate, and transform SQL Server CDC streams over Kafka with Parquet snapshots. Batch jobs processed **100M+ records** into unified datasets in Bigtable.

I redesigned the data-pipeline topology and Bigtable access patterns, removing read-before-write operations and simplifying the pipeline architecture. The change reduced batch runtimes **from 2 days to 8 hours**.

**Technologies:** Apache Beam, Dataflow, Kafka, SQL Server CDC, Parquet, Bigtable

### Low-latency hotel search for an AI assistant
At MakeMyTrip, I owned the Hotel Search API used by the Myra AI chatbot and hotel search bar. The system combined vector similarity search with knowledge-graph traversal to retrieve hotel aspects, delivering **sub-100 ms end-to-end latency**.

I improved p99 latency through in-service embedding inference, parallel Neo4j queries, and Aerospike caching; hotel-highlight lookups were served in **under 20 ms**.

**Technologies:** Java, vector search, Neo4j, Aerospike, embeddings

### Pricing analytics at scale
I developed a Java/Spring Boot pricing analytics microservice that ingested millions of pricing events daily and served latency-sensitive queries. By optimizing schema design, partitioning, and sort keys in distributed ClickHouse, I achieved **18 ms query latency without a caching layer**.

The service enabled real-time price-drop insights that contributed to **8% higher booking conversions**.

**Technologies:** Java, Spring Boot, ClickHouse, event-driven systems

### Service modernization and reliability
I contributed to the re-architecture of a hotel pricing system using gRPC APIs, reducing latency from **1 second to under 100 ms**. I also redesigned the integration-testing framework, reducing feedback time from **40 minutes to 2 minutes**.

At Payoneer, I modernized services from .NET Core 3.1 to .NET 10 and deployed a Shadow Mode Comparator to Kubernetes using Helm and Argo CD.

## Open source

### Qdrant
I contributed to [Qdrant](https://github.com/qdrant/qdrant), an open-source vector database. [PR #10862](https://github.com/qdrant/qdrant/pull/10862) fixed silently empty full-text indexes by adding validation across REST and gRPC.

I’m interested in database internals, distributed systems, storage and indexing, stream processing, and AI infrastructure.

## Beyond production systems

- **LeetCode:** 800+ problems solved; 2000+ rating and Knight Badge
- **Recognition:** Super Tripper of the Month and Dream Team Award (Hotels-AI) at MakeMyTrip

## Contact

- LinkedIn: [linkedin.com/in/gouravb20](https://linkedin.com/in/gouravb20)
- GitHub: [github.com/gouravb20](https://github.com/gouravb20)
- LeetCode: [leetcode.com/u/gouravb20](https://leetcode.com/u/gouravb20)

---

*This profile highlights selected work and engineering outcomes. For implementation details, see the linked repositories and contributions.*
