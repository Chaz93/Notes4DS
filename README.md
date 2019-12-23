# Notes4DS
## 学习计划
| 名称 | 发表日期 | 类别 | 预期截止时间 | issue id | 备注 |
| --- | --- | --- | --- | --- | --- |
| The Google File System | 2003 | BigData | 2019.12 | | | 
| The Chubby lock service for loosely-coupled distributed systems | 2006 | LockService | 2019.12 | | |  	
| Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center | 2011 | Scheduler | 2019.12 |  | [源码](https://github.com/apache/mesos) | 
| The Part-Time Parliaments | 1998 | Consensus | 2020.1 | | | 
| Paxos made simple | 2001 | Consensus | 2020.1	 | | | 
| Bigtable: A Distributed Storage System for Structured Data | 2006 | Storage | 2020.1 | | |  	
| Paxos Made Live – An Engineering Perspective | 2007 | Consensus | 2020.1 | | |
| ZooKeeper: Wait-free coordination for Internet-scale systems | 2010 | Consensus | 2020.1 | | |
| The hadoop distributed file system | 2010 | BigData | 2020.1 | | | 
| SCOPE: parallel databases meet MapReduce | 2012 | BigData | 2020.1 | | |
| Raft: In search of an Understandable Consensus Algorithm | 2014 | Consensus | 2020.1 | | |
| Efficient Replica Maintenance for Distributed Storage Systems | 2006 | Storage | 2020.2 |	| |
| Dynamo: amazon's highly available key-value store | 2007 | Storage | 2020.2 | | | 
| Dryad: Distributed Data-Parallel Programs from Sequential Building Blocks | 2007 | BigData | 2020.2 | | |	
| MapReduce: Simplified Data Processing on Large Clusters | 2008 | BigData | 2020.2 | | | 
| Spark: Cluster computing with working sets | 2010 | BigData | 2020.2 | | | 
| Windows Azure Storage: a highly available cloud storage service with strong consistency | 2011 | Storage | 2020.2 | | |
| Spanner: Google’s Globally-Distributed Database | 2013 | Storage | 2020.2 | | |
| A Characteristic Study on Failures of Production Distributed Data-Parallel Programs | 2013 | BigData | 2020.2| | |
| Fast in-memory transaction processing using RDMA and HTM | 2015 | Storage | 2020.2 | | |	
| Availability in Globally Distributed Storage Systems | 2010 | Storage | 2020.3 | | |
| Finding a needle in Haystack: Facebook’s photo storage | 2010 | Storage | 2020.3 | | | 
| Omega: flexible, scalable schedulers for large compute clusters | 2013 | Scheduler | 2020.3 | | |
| Apache Hadoop YARN: Yet Another Resource Negotiator | 2013 | Scheduler | 2020.3 | | [源码](https://github.com/radlab/sparrow) |
| Sparrow: Distributed, Low Latency Scheduling | 2013 | Scheduler | 2020.4 | | |		
| Apollo: Scalable and Coordinated Scheduling for Cloud-Scale Computing | 2014 | Scheduler | 2020.4 | | |		
| Large-scale cluster management at Google with Borg | 2015 | Scheduler | 2020.4 | | | 
| Hawk: Hybrid Datacenter Scheduling | 2015 | Scheduler | 2020.4 | | |		
| Realtime Data Processing at Facebook | 2016 | BigData | 2020.4 | | |  
| Mercury: Hybrid Centralized and Distributed Scheduling in Large Shared Clusters | 2015 | Scheduler | 2020.5 | | | 
| Tarcil: Reconciling Scheduling Speed and Quality in Large Shared Clusters | 2015 | Scheduler | 2020.5 | | | 
| Tarcil: High Quality and Low Latency Scheduling in Large, Shared Clusters | 2015 | Scheduler | 2020.5 | | | 
| Firmament: Fast, Centralized Cluster Scheduling at Scale | 2016 | Scheduler | 2020.5 | | [源码](https://github.com/camsas/firmament)|
| Efficient queue management for cluster scheduling | 2016 | Scheduler | 2020.6 | | | 
| Eagle: A better hybrid data center scheduler | 2016 | Scheduler | 2020.6 | | | 
| Job-aware Scheduling in Eagle: Divide and Stick to Your Probes | 2016 | Scheduler | 2020.6 | | |
| Canary: A scheduling architecture for high performance cloud computing | 2016 | Scheduler | 2020.6 | | | 
| Profiling a warehouse-scale computer | 2016 | Scheduler | 2020.6 | | |

### 说明
* 读完paper的心得会在相应的issue页面中记录。其中需要记录的有：**文章内容**（*逻辑梳理*），**自己想法** （*是否解决了某个问题的充分条件，是否有更进一步的可能等*）;
* 与文献相关的源码并不能在截止日期前完成，其相应的学习笔记将更新记录在相应的issue页面里;
* 这里不包括动手实现部分，动手实验部分目前会参考MIT的[分布式系统课程](https://pdos.csail.mit.edu/6.824/)里面提供的课程实验来完成，实验完成进度更新在issue上，截止日期为2020.3;
* 该阅读版本主要依据的是[dyweb/papers-notebook](https://github.com/dyweb/papers-notebook#zookeeper) 以及 [ty4z2008/Qix](https://github.com/ty4z2008/Qix/blob/master/ds.md)项目中整理的部分文献，并非最终实际的阅读版本，阅读列表将会一直更新，期待做到终生学习;