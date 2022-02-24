# Benchmark of Kafka: Rust producer  and consumer

Create topic:

```shell
/usr/local/opt/kafka/bin/kafka-topics --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic my-topic
```


Generate:
```shell
cargo run --bin generator 
```

Consume:
```shell
cargo run --bin sink  
```


