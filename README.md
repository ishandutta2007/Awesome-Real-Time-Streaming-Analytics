# Awesome-Real-Time-Streaming-Analytics

## Top Real-Time Streaming Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Continuous Queries, Complex Event Processing & Self-Hosted Stream Analytics*  

**Last updated: October 2026**



This repository tracks notable **commercial streaming analytics platforms** and **open-source projects** that analyze data in motion — detecting patterns, computing aggregations, and triggering actions on continuous event streams with sub-second to second-level latency.



**Examples** include AWS Kinesis Data Analytics, Apache Flink, Confluent Cloud, Google Cloud Dataflow, Databricks Streaming, Azure Stream Analytics, Decodable, Upsolver, DeltaStream, and StarTree Cloud (the category leaders).



**Open-source emphasis**: Streaming analytics is one of the strongest open-source domains. **Apache Flink** leads as the de facto standard for stateful stream processing, **Apache Spark Structured Streaming** provides unified batch/stream, and **Kafka Streams**/**ksqlDB** deliver Kafka-native analytics. **Apache Beam** enables portable pipelines, **RisingWave** and **Materialize** bring streaming SQL databases, and **Arroyo** offers Rust-based processing. **Apache Druid** and **Apache Pinot** handle real-time OLAP. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Kinesis Data Analytics](https://aws.amazon.com/kinesis/data-analytics/)**  

  **AWS's managed stream analytics** — SQL or Apache Flink for real-time processing . **No infrastructure to manage** . **Best for AWS-native stream analytics** .



- **[Confluent Cloud](https://www.confluent.io/confluent-cloud/)**  

  **Managed Kafka with ksqlDB and Flink** — stream processing without cluster management . **Best for Kafka-native analytics** .



- **[Google Cloud Dataflow](https://cloud.google.com/dataflow)**  

  **Google's fully managed stream and batch processing** based on Apache Beam . **Best for GCP-native streaming** .



- **[Databricks Streaming](https://www.databricks.com/)**  

  **Spark Structured Streaming on lakehouse** — Delta Live Tables for streaming pipelines . **Best for lakehouse streaming** .



- **[Azure Stream Analytics](https://azure.microsoft.com/en-us/products/stream-analytics/)**  

  **Microsoft's real-time analytics** — SQL-like queries on streaming data . **Best for Azure-native analytics** .



- **[Decodable](https://www.decodable.co/)**  

  **Managed stream processing** — SQL-based pipelines on Apache Flink . **Best for simple streaming ETL** .



- **[Upsolver](https://www.upsolver.com/)**  

  **Stream data lake platform** — real-time ingestion, transformation, and analytics . **Best for streaming into data lakes** .



- **[DeltaStream](https://deltastream.io/)**  

  **Serverless streaming SQL** — query Kafka with SQL . **Best for SQL-based stream processing** .



- **[StarTree Cloud](https://startree.ai/)**  

  **Managed Apache Pinot** — real-time OLAP for user-facing analytics . **Best for real-time analytics** .



## Open-Source GitHub Projects



### Stream Processing Engines



- **[Apache Flink](https://github.com/apache/flink)**  

  **The de facto standard for stateful stream processing**, Apache-2.0 licensed with **24,000+ GitHub stars** . **True event-at-a-time processing** with exactly-once semantics, event-time processing, and sophisticated windowing . **Savepoints for versioned state migration** and **backpressure monitoring** . **Handles millions of events per second** with millisecond latency . **The engine behind Alibaba's Singles' Day (2.5 billion events/second)** . **Best for mission-critical, stateful stream processing at scale** .



- **[Apache Spark Structured Streaming](https://github.com/apache/spark)**  

  **Unified batch and stream processing**, Apache-2.0 licensed with **39,000+ GitHub stars** . **Same API for batch and streaming** — DataFrame/Dataset API . **Micro-batch processing with exactly-once semantics** . **Best for teams already using Spark** .



- **[Kafka Streams](https://github.com/apache/kafka)**  

  **Stream processing library for Kafka**, Apache-2.0 licensed . **No separate cluster** — runs in your application . **Exactly-once semantics and interactive queries** . **Best for Kafka-native stream processing** .



- **[ksqlDB](https://github.com/confluentinc/ksql)**  

  **Streaming SQL for Kafka**, Confluent Community License . **SQL interface for Kafka Streams** . **Continuous queries, materialized views, and pull queries** . **Best for SQL-proficient teams** .



- **[Apache Beam](https://github.com/apache/beam)**  

  **Unified programming model for batch and stream**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Portable across Flink, Spark, Dataflow, and Samza** . **Best for portable pipelines** .



- **[Arroyo](https://github.com/ArroyoSystems/arroyo)**  

  **Modern stream processing engine in Rust**, Apache-2.0 licensed with **4,000+ GitHub stars** . **SQL-based pipelines without JVM** . **Serverless deployment model** . **Best for lightweight, modern stream processing** .



### Streaming Databases



- **[RisingWave](https://github.com/risingwavelabs/risingwave)**  

  **Streaming database for real-time analytics**, Apache-2.0 licensed with **7,000+ GitHub stars** . **PostgreSQL-compatible SQL** . **Streaming SQL with materialized views** . **S3 as primary storage** . **Best for streaming SQL with database-like experience** .



- **[Materialize](https://github.com/MaterializeInc/materialize)**  

  **Streaming database built on Timely Dataflow**, BSL licensed (free for most uses) . **PostgreSQL-compatible** . **Strong consistency and exactly-once semantics** . **Best for streaming SQL with strong consistency** .



- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**  

  **The leading columnar analytical database**, Apache-2.0 licensed with **35,000+ GitHub stars** . **Real-time ingestion and sub-second queries** . **Best for large-scale analytics** .



### Real-Time OLAP



- **[Apache Druid](https://github.com/apache/druid)**  

  **Real-time analytics database**, Apache-2.0 licensed with **13,000+ GitHub stars** . **Sub-second queries on streaming data** . **Best for real-time analytics** .



- **[Apache Pinot](https://github.com/apache/pinot)**  

  **Real-time distributed OLAP datastore**, Apache-2.0 licensed with **5,000+ GitHub stars** . **User-facing analytics** . **Best for real-time analytics at scale** .



- **[Apache Doris](https://github.com/apache/doris)**  

  **Real-time analytical database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **High-performance SQL analytics** . **Best for real-time analytics** .



- **[StarRocks](https://github.com/StarRocks/starrocks)**  

  **High-performance analytical database**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Real-time analytics with lakehouse integration** . **Best for modern analytics** .



### Data Movement & CDC



- **[Debezium](https://github.com/debezium/debezium)**  

  **The leading open-source CDC platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Captures row-level changes from databases** . **Best for database replication and real-time sync** .



- **[Benthos (Redpanda Connect)](https://github.com/redpanda-data/connect)**  

  **Stream processing without code**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Declarative YAML configuration for streaming ETL** . **Best for code-free stream pipelines** .



- **[Vector](https://github.com/vectordotdev/vector)**  

  **High-performance observability data pipeline**, MPL-2.0 licensed with **18,000+ GitHub stars** . **Collect, transform, and route logs, metrics, and events** . **Best for observability data** .



### Additional Strong Open-Source Options



- **Apache Samza** — Stream processing on Kafka .

- **Apache Storm** — Real-time computation (legacy) .

- **Apache Heron** — Twitter's stream processing (retired) .

- **Apache Apex** — Enterprise stream processing (retired) .

- **Apache Flume** — Log aggregation (legacy) .

- **Logstash** — Data collection and transformation .

- **Fluentd** — Unified logging layer .

- **Fluent Bit** — Lightweight log processor .

- **Apache SeaTunnel** — High-performance data integration .

- **Apache NiFi** — Data flow automation .



**Frameworks for building custom real-time streaming analytics solutions**: Combine **Apache Flink** for mission-critical stateful stream processing with exactly-once semantics . Use **Spark Structured Streaming** for teams already using Spark . Deploy **Kafka Streams** or **ksqlDB** for Kafka-native analytics . Choose **RisingWave** or **Materialize** for streaming SQL with database-like experience . Integrate **Apache Druid** or **Apache Pinot** for real-time OLAP . Use **Arroyo** for lightweight Rust-based processing . Note that true managed streaming analytics with global infrastructure, automatic scaling, and vendor-supported SLAs (Kinesis Data Analytics, Confluent Cloud, Dataflow) remain primarily commercial territory; open-source stacks provide strong stream processing, streaming SQL, and real-time OLAP foundations that require integration for complete analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Streaming analytics platforms handle high-volume data in motion. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: Flink uses Apache-2.0, ksqlDB uses Confluent Community License, Materialize uses BSL (free for most uses), and RisingWave uses Apache-2.0. Verify licensing against your use case before committing .

- **State management is the hard part** — Flink's savepoints, Kafka Streams' state stores, and Materialize's arrangements all require operational expertise. Plan for state backup, migration, and recovery .

- **Latency vs. throughput trade-offs** — Flink processes event-at-a-time for lowest latency; Spark Structured Streaming uses micro-batches for higher throughput. Choose based on your latency requirements .

- The open-source ecosystem provides strong stream processing, streaming SQL, and real-time OLAP foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for data engineers, streaming architects, and organizations seeking streaming analytics sovereignty.**  

Let's make real-time streaming analytics more open, transparent, and performant.
