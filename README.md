# multinode-kafka-cluster

#### kafka-cluster
##### Kafka Service Ports
- default port : 9092

##### ZooKeeper Service Ports
- clientPort : 2181
- peerport : 2888
- leaderport : 3888
- uid=1000(appuser) gid=1000(appuser)

```
mkdir -p kafka-data kafka-varlog zookeeper-data zookeeper-varlog
chown -R 1000.1000 kafka-data kafka-varlog zookeeper-data zookeeper-varlog
```
