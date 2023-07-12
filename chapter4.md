# Chapter Four: Why build a data lake?

As business grows, there will be more and more data sources and hard to keep track of.

There should be a unified way (or ways) of requesting  data from a unified source.

It's encouraged to replicate all sources into a single data store. This collection of replicated source is called a data lake.

Implementation‐wise, a data lake is very often a database with its own set of rules and customers, designed to handle incredibly large amounts of data and optimize that data for analytics workloads.

## Reasons to Build a Data Lake Summarized
### One Technology
Queries can access all data in one language.

### JOINing
Makes joining data from disparate data sources much easier.

### Robust Query Writing
Querying from your own database will not only be faster but it will be cheaper, as API quotas can be expensive.

### Performance
Source data might be from an actual production database, which could affect the performance of the application. 

Data lakes ideally handle ad‐hoc analytical queries independently of the production environment. It's possible to scale up resources on a data lake to be able to query data even faster. 

Being a collection of replicas leads to a more fault‐tolerant data stack.

### Future Development
Collecting all sources into one data store is a necessary step for building the rest of the modern data stack. The warehouse layer of transformations requires a data lake at its foundation.