# 3NodeKafkaCluster_TaskD

A 3 Node Apache Kafka cluster using Docker that demonstrates Pub-Sub messaging, with a Zookeeper ensemble created to manage the Kafka Cluster.

# Instructions
To set up:
```
docker-compose up
```

Update host file on /etc/hosts (UNIX) or C:\Windows\System32\Drivers\etc\hosts (Windows)
```
# Add this line
127.0.0.1 kafka-1 kafka-2 kafka-3 zookeeper-1 zookeeper-2 zookeeper-3
```

# Demonstration
The demonstration of the:
- Successful implementation of the Pub-Sub messaging system
- Successful management of the failure of the master node in the cluster (i.e. Another node takes over as master node)

can be found in the writeup submitted.