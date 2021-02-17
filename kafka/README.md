# Kafka

Kafka sample examples

## Codes

```
./bin/zookeeper-server-start.sh config/zookeeper.properties 

cat config/server.properties 
./bin/kafka-server-start.sh config/server.properties 

cp server.properties server2.properties 
vi server2.properties 
./bin/kafka-server-start.sh config/server2.properties 

./kafka-topics.sh 
./kafka-topics.sh --bootstrap-server localhost:9092 --describe --topic topic10
./kafka-topics.sh --bootstrap-server localhost:9092 --describe --topic topic1
./kafka-topics.sh --bootstrap-server localhost:9092 --delete --topic topic1
./kafka-topics.sh --bootstrap-server localhost:9092 --list --topic topic1
./kafka-topics.sh --bootstrap-server localhost:9092 --list
./kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic topic10
./kafka-console-producer.sh --bootstrap-ser localhost:9092 --topic topic10 write
./kafka-consumer-groups.sh --bootstrap-server localhost:9092 --list
./kafka-consumer-groups.sh --bootstrap-server localhost:9092 --describe --group console-consumer-{consumer-number}
pip install numpy
pip install pandas
```
