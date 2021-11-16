# multinode-kafka-cluster

#### kafka-cluster
##### Kafka(broker) Service Ports
- default port : 9092

##### ZooKeeper Service Ports
- clientPort : 2181
- peerport : 2888
- leaderport : 3888

##### 디렉터리 생성
```
mkdir -p kafka-data kafka-varlog zookeeper-data zookeeper-varlog
```
##### 디렉터리 권한(chown) 변경
- uid=1000(appuser) gid=1000(appuser)
```
chown -R 1000.1000 kafka-data kafka-varlog zookeeper-data zookeeper-varlog
```
