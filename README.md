# kafka-zk-connection
Java adapter to create a connection to Kafka only based on the zk host list and does not need broker list definition

This project aims to eliminate the need to specify Kafka broker list while making a connection to Kafka. The client should only specify the minimal zookeeper list, and after that the code will connect to zookeeper and will automatically figure out the Kafka brokers in the cluster and then act as an adapter for making consumer and producer connections.


