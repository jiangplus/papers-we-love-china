# Papers We Love

Papers We Love China is a open group with a focus on reading and sharing computer science papers. It is also a place for people to share their ideas and experiences of building complex computing systems.

Here is the curated list of the historic talks.

Papers We Love 是一个全球性的社区网络，主要活动是分享计算机科学和相关领域的经典论文和前沿研究，包括但不限于操作系统，分布式系统，数据库，网络通讯，算法，逻辑等领域。我们欢迎不同背景但对此主题感兴趣的工程师，研究员，爱好者共同阅读、分享和讨论这些基础研究工作及其应用实践。

以下是 PWL China 分享过的主题列表。

## 2020-12-20

由 @张茄子，@Gonnyy 分享他们在 Intel Optane 上设计高性能 KV 相关的主题，并有 Persistent Memory 相关的圆桌讨论。

## 2020-11-29

Don’t Settle for Eventual:
Scalable Causal Consistency for Wide-Area Storage with COPS

马天猫分享关于分布式系统中因果一致性（Casual+）的论文 COPS.

分享人：马天猫，在读 PhD，字节跳动基础架构实习生。

强一致性（linearizable，sequential）的分布式系统在全球多数据中心的场景下，可用性和延迟很难满足许多应用的需求。CMU 在 sosp11 发表的 COPS，面向全球多数据中心场景，探索在保证高可用，低延迟，可扩展的场景下最高的一致性级别，提出了 Causal+ 的一致性级别，并设计了分布式 KV 存储系统 COPS.

[论文链接](https://www.cs.cmu.edu/~dga/papers/cops-sosp2011.pdf)

## 2020-07-12

Andromeda: Performance, Isolation, and Velocity
at Scale in Cloud Network Virtualization

由 SmartX 的张凯分享关于 Google Cloud 的网络架构，论文发表于 NSDI'18.

[论文链接](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-dalton.pdf)

## 2020-06-14

由 @jiangplus 分享 Apple 的分布式数据库 FoundationDB 的架构。

## 2020-05-10

MapReduce: Simplified Data Processing on Large Clusters

由 要没时间了 分享 Google MapReduce 的经典论文。

[论文链接](https://research.google.com/archive/mapreduce-osdi04.pdf)

The Snowflake Data Warehouse

由 @jiangplus 分享，关于云原生数据仓库的设计。

[论文链接](http://info.snowflake.net/rs/252-RFO-227/images/Snowflake_SIGMOD.pdf)

## 2019-08-11

PacificA: Replication in Log-Based Distributed Storage Systems 

分享人：张凯，SmartX

PacificA是微软为大规模分布式存储系统开发的一个通用复制框架，该框架简单，实用，提供强一致性，并且可以适配不同的复制策略。它对于我们理解分布式系统的强一致性，构建工程化的分布式系统有很好的指导意义。

[论文链接](https://www.microsoft.com/en-us/research/wp-content/uploads/2008/02/tr-2008-25.pdf)

Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases 

分享人：@jiangplus

Amazon Aurora 云原生数据库服务的论文，有独特的数据复制和云原生设计，并且也是计算存储分离和 share-everything 架构的经典。

[论文链接](https://awsmedia.awsstatic-china.com/blog/2017/aurora-design-considerations-paper.pdf)




