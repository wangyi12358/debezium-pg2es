# Debezium pg2es

Debezium pg2es is a tool to replicate data from PostgreSQL to Elasticsearch using Debezium and Kafka.

## Environment variables

## Usage

### Send message to Kafka
  
```bash
docker exec -it kafka /bin/bash
kafka-console-producer --topic test-topic --bootstrap-server localhost:9092
```

### ES setup password

```bash
docker exec -it elasticsearch /bin/bash
bin/elasticsearch-setup-passwords interactive
```