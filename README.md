# DS201 Exercise 14

## Read Repair

**In this hands-on lab, you will:**
*	Simulate an inconsistent replica node by deleting its data files
*	Force a read repair by requesting query results from all replica nodes

Consistency is the tricky challenge for distributed systems. As distributed systems trade-off consistency for performance, some of the nodes in a cluster may become inconsistent. When Cassandra notices these inconsistencies, it takes steps to resolve them. This resolution is the role of read repair.

## Start the hands-on lab:

[![Open in KataPod](https://github.com/DataStax-Academy/katapod-shared-assets/blob/main/images/open-in-katapod.png)](https://gitpod.io/##https://github.com/DataStax-Academy/ds201-lab14/)