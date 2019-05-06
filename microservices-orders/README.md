![image](../images/confluent-logo-300-2.png)

# Overview

This self-paced tutorial provides exercises for developers to apply the basic principles of streaming applications, by using a small demo microservice ecosystem built with Kafka Streams.

![image](docs/images/microservices-demo.jpg)

# Documentation

You can find the documentation for running this demo and its accompanying tutorial at [https://docs.confluent.io/current/tutorials/examples/microservices-orders/docs/index.html](https://docs.confluent.io/current/tutorials/examples/microservices-orders/docs/index.html)

# USAGE
docker-compose up
docker exec -it ksql-cli ksql http://ksql-server:8088
list topics; list tables; list streams; list queries;
docker exec -it broker bash
kafka-topics --zookeeper $ZK --list

http://localhost:18894/v1/orders/2/
http://localhost:5601/app/kibana#/dashboard/Microservices
