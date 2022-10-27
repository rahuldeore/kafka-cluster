What is this project ?
=======================
This project is a getting started guide to kafka. There are three setup discussed. Manual setup of standalone 
kafka server, docker compose standalone server, docker compose kafka cluster.

Manual setup
------------
This tutorial is derived from original documentation available at the kafka website: https://kafka.apache.org/documentation.html#quickstart 
Other resources referred during this learning:
- https://www.baeldung.com/ops/kafka-docker-setup
- https://docs.docker.com/compose/reference/

High level steps tested with kafka version 3.3.1
1. Download kafka desktop version
2. Start zookeeper (currently zookeeper is a dependency for kafka). Make a note of port. Default is 2181
3. Start kafka server. Make a note of the port
4. Kafka standalone is setup !
5. Some simple examples below.
   1. Test producer consumer
   2. Test kafka-connect (File read example)
   3. Check messages from beginning and / or listen for new
   4. 

Docker compose standalone server
--------------------------------
Please take a look at the docker-compose-standalone.yml in this project. You can run the
file using docker-compose up -d -f docker-compose-standalone.yml

Docker compose cluster config
-----------------------------
Please take a look at the docker-compose-cluster.yml in this project. You can run the
file using docker-compose up -d -f docker-compose-cluster.yml


