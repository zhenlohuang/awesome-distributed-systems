# awesome-distributed-systems
A curated list of awesome distributed systems books, papers, resources and shiny things.

## Bootcamp
* [CAP Theorem](http://en.wikipedia.org/wiki/CAP_theorem)
* [Fallacies of Distributed Computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
* [Distributed systems theory for the distributed engineer](http://the-paper-trail.org/blog/distributed-systems-theory-for-the-distributed-systems-engineer/)   
Chinese version: [面向分布式系统工程师的分布式系统理论](http://blog.xiayf.cn/2014/08/10/Distributed-systems-theory-for-the-distributed-systems-engineer/)

## Books
* [Distributed Systems for fun and profit](http://book.mixu.net/distsys/single-page.html)
* [Distributed Systems Concepts and Design(Fifth Edition) - George Coulouris](https://azmuri.files.wordpress.com/2013/09/george-coulouris-distributed-systems-concepts-and-design-5th-edition.pdf)
* [Distributed Systems Principles and Paradigms - Andrew Tanenbaum](http://sist.sysu.edu.cn/~wuweig/DCC/DistributedSystemsPrinciplesandParadigms\(2nd%20edition\)-2007-Tanenbaum.pdf)
* [走向分布式](http://dcaoyuan.github.io/papers/pdfs/Scalability.pdf)

## Courses
* [Cloud Computing Concepts](https://class.coursera.org/cloudcomputing-001), University of Illinois
* [CMU: Distributed Systems](http://www.cs.cmu.edu/%7Edga/15-440/F12/syllabus.html) in Go Programming Language
* [Principles of Distributed Computing](http://dcg.ethz.ch/lectures/podc_allstars/)
* [Distributed Systems Fall 2015](http://www.andrew.cmu.edu/course/95-702/)
* [Distributed Systems - MIT](http://nil.csail.mit.edu/6.824/2015/)
* [Introduction to Distributed System Design - Google Code University](http://www.hpcs.cs.tsukuba.ac.jp/%7Etatebe/lecture/h23/dsys/dsd-tutorial.html)

## Papers

### Storage
* [Dynamo: Amazon's Highly Available Key Value Store](http://bnrg.eecs.berkeley.edu/%7Erandy/Courses/CS294.F07/Dynamo.pdf)
* [Bigtable: A Distributed Storage System for Structured Data](http://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
* [The Google File System](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en/us/archive/gfs-sosp2003.pdf)
* [Cassandra: A Decentralized Structured Storage System](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.161.6751&rep=rep1&type=pdf)
* [CRUSH: Controlled, Scalable, Decentralized Placement of Replicated Data](http://www.ssrc.ucsc.edu/Papers/weil-sc06.pdf)
* [Replication, History, and Grafting in the Ori File System](http://delivery.acm.org/10.1145/2530000/2522721/p151-mashtizadeh.pdf?ip=103.3.61.253&id=2522721&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2EC42B82B87617960C&CFID=732657948&CFTOKEN=82551724&__acm__=1448289434_3a986bc8befa98334753cfeaa470baae) ([Project Home](http://ori.scs.stanford.edu))
* [Availability in Globally Distributed Storage Systems](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/36737.pdf)
* [Sheepdog: Distributed Storage System for KVM](https://github.com/ty4z2008/Qix/blob/master/ds.md)
* [PacificA: Replication in Log-Based Distributed Storage Systems](http://research.microsoft.com:8082/pubs/66814/tr-2008-25.pdf)
* [Object Storage on CRAQ, High-throughput chain replication for read-mostly workloads](http://sns.cs.princeton.edu/docs/craq-usenix09.pdf)[code](https://github.com/jterrace/craq)
* [Finding a needle in Haystack: Facebook’s photo storage](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf)
* [Windows Azure Storage: A Highly Available Cloud Storage Service with Strong Consistency](http://www-bcf.usc.edu/%7Eminlanyu/teach/csci599-fall12/papers/11-calder.pdf)
* [Efficient Replica Maintenance for Distributed Storage Systems](http://oceanstore.cs.berkeley.edu/publications/papers/pdf/carbonite06.pdf)
* [PADS: A Policy Architecture for Distributed Storage Systems](https://www.cs.nyu.edu/rgrimm/papers/nsdi09.pdf)

### Databases
* [Spanner: Google’s Globally-Distributed Database](http://static.googleusercontent.com/media/research.google.com/zh-CN//archive/spanner-osdi2012.pdf)
* [Calvin: Fast Distributed Transactions For Partitioned Database Systems](http://highscalability.com/blog/2013/5/23/paper-calvin-fast-distributed-transactions-for-partitioned-d.html)
* [Tera - 高性能、可伸缩的结构化数据库](https://github.com/ty4z2008/Qix/blob/master/ds.md)

### Resource Management
* [Apache Hadoop YARN: Yet Another Resource Negotiator](https://www.sics.se/~amir/files/download/dic/2013%20-%20Apache%20Hadoop%20YARN:%20Yet%20Another%20Resource%20Negotiator%20\(SoCC\).pdf)
* [Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center](https://www.cs.berkeley.edu/~alig/papers/mesos.pdf)

### Data Processing
* [MapReduce: Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/zh-CN//archive/mapreduce-osdi04.pdf)


### Query Processing
* [Design and Implementation of a Query Processor for a Trusted Distributed Data Base Management System](http://www.utdallas.edu/%7Ebxt043000/Publications/Journal-Papers/DAS/J16_Design_and_Implementation_of_a_Distributed_Query_Processor.pdf)

### Messaging Systems
* [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)   
Chinese version [日志：每个软件工程师都应该知道的有关实时数据的统一概念](http://www.oschina.net/translate/log-what-every-software-engineer-should-know-about-real-time-datas-unifying?lang=chs&page=1#)
* [Kafka: a Distributed Messaging System for Log Processin](http://notes.stephenholiday.com/Kafka.pdf)

### Distributed Consensus
* [The Part Time Parliament](http://research.microsoft.com/en-us/um/people/lamport/pubs/lamport-paxos.pdf), Lamport's original Paxos paper, but it's a bit difficult to understand.
* [Paxos Made Simple](http://research.microsoft.com/en-us/um/people/lamport/pubs/paxos-simple.pdf), a more terse readable Paxos paper by Lamport himself.
* [The Chubby Lock Service for loosely coupled distributed systems](http://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)
* [Paxos made live - An engineering perspective](http://research.google.com/archive/paxos_made_live.html)
* [Raft Consensus Algorithm](https://raftconsensus.github.io/)
* [Paxos vs Raft](https://ramcloud.stanford.edu/%7Eongaro/userstudy/)

### Others
* [Sinfonia: a new paradigm for building scalable distributed systems](http://www.sosp2007.org/papers/sosp064-aguilera.pdf)
* [Distributed Systems and the End of the API](http://writings.quilt.org/2014/05/12/distributed-systems-and-the-end-of-the-api/)
* [Designs, Lessons and Advice from Building Large Distributed Systems](http://www.cs.cornell.edu/projects/ladis2009/talks/dean-keynote-ladis2009.pdf)
* [Testing a Distributed System](http://queue.acm.org/detail.cfm?ref=rss&id=2800697)
* [Time, Clocks, and the Ordering of Events in a Distributed System](http://research.microsoft.com/en-us/um/people/lamport/pubs/time-clocks.pdf)

## Blogs and other reading links
* [What are some good resources for learning about distributed computing? Why?](https://www.quora.com/What-are-some-good-resources-for-learning-about-distributed-computing-Why)