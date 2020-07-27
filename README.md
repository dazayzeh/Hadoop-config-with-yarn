# Hadoop-config-with-yarn
Hadoop setup - distributed mode with yarn locally.

#Starting the cluster
1. Run `start-yarn.sh`
2. Run `jps` and essential things to see are:
  NodeManager - (Related to YARN)
  ResourceManager - (Related to YARN)
  NameNode - (Related to HDFS)
  DataNode - (Related to HDFS)
  SecondaryNameNode - (Related to HDFS)
3. Now you are ready to run commands.
4. At the end to stop everthing run `stop-dfs.sh` 


