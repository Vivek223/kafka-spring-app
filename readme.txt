This is example app to demonstrate kafka integration with spring boot java app.

How to start kafka locally--
Kafka-home=D:\tools\kafka_2.13-3.6.1

Stpe1: Start the zookeeper server
D:\tools\kafka_2.13-3.6.1\bin\windows>zookeeper-server-start.bat ..\..\config\zookeeper.properties

Step2: Start the Kafka server
D:\tools\kafka_2.13-3.6.1\bin\windows>kafka-server-start.bat ..\..\config\server.properties