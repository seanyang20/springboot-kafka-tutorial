# Kafka with Spring Boot Tutorial



First mini Kafka project using Spring Boot


### Prerequisites


- Spring Boot Framework
- IntelliJ
- Apache Kafka


## Getting Started


### Installing

- Download the kafka zip file from Apache Kafka (first link)
  - https://www.apache.org/dyn/closer.cgi?path=/kafka/3.4.0/kafka_2.13-3.4.0.tgz
- Clone and unzip the project directory
- Cd into kafka folder and started Zookeepr and Kafka broker service in two separate terminals
  - Run the following commands in order to start all services in the correct order:
    ```
    # Start the ZooKeeper service
    $ bin/zookeeper-server-start.sh config/zookeeper.properties
    ```
    
    Open another terminal session and run:
    
    ```
    # Start the Kafka broker service
    $ bin/kafka-server-start.sh config/server.properties
    ```
    
    Once all services ha`ve successfully launched, you will have a basic Kafka environment running and ready to use.


