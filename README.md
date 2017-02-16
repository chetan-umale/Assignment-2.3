Q1-All components of Hadoop 1.x.
answer:
The major components of Hadoop 1.x are 
1.HDFS
2.MapReduce

1.HDFS:
HDFS is a distributed file system which is capable of storing large volumes of data on commodity hardware.It also uses blocks to store files but differs from traditional file systems by storing blocks contoguous memory locations thereby improving access time.
HDFS is further divided into 2 sub-components:

1.1 Name node:
The name node is the master node and is responsible for file system namespace and controls access to files by clients.

1.2 Data node:
The data nodes handles read-write requests from clients and sactually stores the blocks.They are responsible for creation,deletion and replication of data blocks.

2.MapReduce:
MapReduce is the  data processing paradigm used by hadoop.It is a batch processing programming model.

2.1 Job Tracker:
It assigns the new MapReduce tasks to task trackers and also reassigns the tasks whose execution failed.

2.2 Task Trackers:
Task tracker actually execute the MapReduce tasks  and sends it status back to job tracker. 
