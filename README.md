# Kafka
# Start Zookeeper
 * .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
# Start Kafka Server
  * .\bin\windows\kafka-server-start.bat .\config\server.properties
# Topic
  * bin\windows\kafka-console-consumer.bat --topic kafka --from-beginning --bootstrap-server localhost:9092
