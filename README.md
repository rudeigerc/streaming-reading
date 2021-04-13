# Reading List for Stream Processing

## Table of Contents

- [Reading List for Stream Processing](#reading-list-for-stream-processing)
  - [Table of Contents](#table-of-contents)
  - [Books](#books)
  - [Surveys](#surveys)
  - [Stream Processing Systems](#stream-processing-systems)
  - [Stream Join](#stream-join)
  - [Elasticity](#elasticity)
    - [Queuing Theory](#queuing-theory)
    - [State Migration](#state-migration)
  - [BSP](#bsp)
  - [Autoscaling](#autoscaling)
  - [State Management](#state-management)
    - [Storage](#storage)
  - [Hardware](#hardware)
  - [Benchmarking](#benchmarking)
  - [Cluster Resource Management](#cluster-resource-management)
  - [Misc](#misc)

## Books

- [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](http://streamingsystems.net/), O'Reilly Media, Inc., 2018
- [Stream Processing with Apache Flink: Fundamentals, Implementation, and Operation of Streaming Applications](https://www.amazon.com/Stream-Processing-Apache-Flink-Implementation/dp/149197429X), O'Reilly Media, Inc., 2019

## Surveys

- [A Comprehensive Survey on Parallelization and Elasticity in Stream Processing](https://doi.org/10.1145/3303849), ACM Computing Surveys, 2019
- [Hardware-Conscious Stream Processing: A Survey](https://doi.org/10.1145/3385658.3385662), ACM SIGMOD Record, 2020
- [Resource Management and Scheduling in Distributed Stream Processing Systems: A Taxonomy, Review, and Future Directions](https://doi.org/10.1145/3355399), ACM Computing Surveys, 2020
- [A Survey on the Evolution of Stream Processing Systems](https://arxiv.org/abs/2008.00842), arXiv, 2020

## Stream Processing Systems

- [S4: Distributed Stream Computing Platform](https://ieeexplore.ieee.org/abstract/document/5693297), ICDMW, 2010
- [Discretized Streams: An Efficient and Fault-Tolerant Model for Stream Processing on Large Clusters](https://www.usenix.org/conference/hotcloud12/workshop-program/presentation/zaharia), HotCloud, 2012
- [Naiad: a timely dataflow system](https://doi.org/10.1145/2517349.2522738), SOSP, 2013
- [MillWheel: fault-tolerant stream processing at internet scale](https://doi.org/10.14778/2536222.2536229), VLDB, 2013
- [Storm@twitter](https://doi.org/10.1145/2588555.2595641), SIGMOD, 2014
- [Twitter Heron: Stream Processing at Scale](https://doi.org/10.1145/2723372.2742788), SIGMOD, 2015
- [The dataflow model: a practical approach to balancing correctness, latency, and cost in massive-scale, unbounded, out-of-order data processing](https://doi.org/10.14778/2824032.2824076), VLDB, 2015
- [Apache Flink™: Stream and Batch Processing in a Single Engine](http://sites.computer.org/debull/A15dec/p28.pdf), Bulletin of the TCDE, 2015
- [StreamScope: Continuous Reliable Distributed Processing of Big Data Streams](https://www.usenix.org/conference/nsdi16/technical-sessions/presentation/lin), NSDI, 2016
- [Samza: stateful scalable stream processing at LinkedIn](https://doi.org/10.14778/3137765.3137770), VLDB, 2017
- [State management in Apache Flink®: consistent stateful distributed stream processing](https://doi.org/10.14778/3137765.3137777), VLDB, 2017
- [Structured Streaming: A Declarative API for Real-Time Applications in Apache Spark](https://doi.org/10.1145/3183713.3190664), SIGMOD, 2018
- [A Cloud Native Platform for Stateful Streaming](https://arxiv.org/abs/2006.00064), arXiv, 2020.

## Stream Join

- [Providing streaming joins as a service at Facebook](https://doi.org/10.14778/3229863.3229869), VLDB, 2018
- [AJoin: ad-hoc stream joins at scale](https://doi.org/10.14778/3372716.3372718), VLDB, 2019

## Elasticity

- [Stela: Enabling Stream Processing Systems to Scale-in and Scale-out On-demand](https://ieeexplore.ieee.org/abstract/document/7484160), IC2E, 2016
- [Minimizing cost by reducing scaling operations in distributed stream processing](https://doi.org/10.14778/3317315.3317316), VLDB, 2019
- [Elasticutor: Rapid Elasticity for Realtime Stateful Stream Processing](https://doi.org/10.1145/3299869.3319868), SIGMOD, 2019
- [Turbine: Facebook’s Service Management Platform for Stream Processing](https://doi.org/10.14778/3137765.3137777), ICDE, 2020
- [Move Fast and Meet Deadlines: Fine-grained Real-time Stream Processing with Cameo](https://www.usenix.org/conference/nsdi21/presentation/xu), NSDI, 2021

### Queuing Theory

- [Elastic Stream Processing with Latency Guarantees](https://ieeexplore.ieee.org/document/7164926) (Nephele), ICDCS, 2015
- [DRS: Auto-Scaling for Real-Time Stream Analytics](https://ieeexplore.ieee.org/document/8024162), IEEE/ACM TON, 2017

### State Migration

- [Megaphone: latency-conscious state migration for distributed streaming dataflows](https://doi.org/10.14778/3329772.3329777), VLDB, 2019

## BSP

- [Drizzle: Fast and Adaptable Stream Processing at Scale](https://doi.org/10.1145/3132747.3132750), SOSP, 2017
- [Riffle: optimized shuffle service for large-scale data analytics](https://doi.org/10.1145/3190508.3190534), EuroSys, 2018
- [Prompt: Dynamic Data-Partitioning for Distributed Micro-batch Stream Processing Systems](https://doi.org/10.1145/3318464.3389713), SIGMOD, 2020

## Autoscaling

- [Three steps is all you need: fast, accurate, automatic scaling decisions for distributed streaming dataflows](https://www.usenix.org/conference/osdi18/presentation/kalavri) (DS2), OSDI, 2018
- [Autopilot: workload autoscaling at Google](https://doi.org/10.1145/3342195.3387524), EuroSys, 2020
- [Auto-sizing for Stream Processing Applications at LinkedIn](https://www.usenix.org/conference/hotcloud20/presentation/singh) (Sage), HotStorage, 2020

## State Management

### Storage

- [Optimizing space amplification in RocksDB](https://research.fb.com/publications/optimizing-space-amplification-in-rocksdb/), CIDR, 2017
- [FASTER: A Concurrent Key-Value Store with In-Place Updates](https://doi.org/10.1145/3183713.3196898), SIGMOD, 2018
- [In support of workload-aware streaming state management](https://www.usenix.org/conference/hotstorage20/presentation/kalavri), HotStorage, 2020

## Hardware

- [Analyzing efficient stream processing on modern hardware](https://doi.org/10.14778/3303753.3303758), VLDB, 2019

## Benchmarking

- [Nexmark benchmark suite](https://beam.apache.org/documentation/sdks/java/testing/nexmark/)
- [Benchmarking cloud serving systems with YCSB](https://doi.org/10.1145/1807128.1807152), SoCC, 2010
- [Benchmarking Distributed Stream Data Processing Systems](https://ieeexplore.ieee.org/abstract/document/8509390), ICDE, 2018

## Cluster Resource Management

- [Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center](https://www.usenix.org/conference/nsdi11/mesos-platform-fine-grained-resource-sharing-data-center), NSDI, 2011
- [Omega: flexible, scalable schedulers for large compute clusters](https://doi.org/10.1145/2465351.2465386), EuroSys, 2013
- [Apache Hadoop YARN: yet another resource negotiator](https://doi.org/10.1145/2523616.2523633), SoCC, 2013
- [Large-scale cluster management at Google with Borg](https://doi.org/10.1145/2741948.2741964), EuroSys, 2015
- [Twine: A Unified Cluster Management System for Shared Infrastructure](https://www.usenix.org/conference/osdi20/presentation/tang), OSDI, 2020

## Misc

- [TerseCades: Efficient Data Compression in Stream Processing](https://www.usenix.org/conference/atc18/presentation/pekhimenko), USENIX ATC, 2018 (compression)
- [Integrating scale out and fault tolerance in stream processing using operator state management](https://doi.org/10.1145/2463676.2465282) (SEEP), SIGMOD, 2013
