# Spring-boot-ELK-stash

Reference - https://www.javainuse.com/spring/springboot-microservice-elk

---------
Steps to make it run and log using ELK(Elaticsearch - Logstash - Kibana)

Start Elasticsearch(http://localhost:9200), kibana(http://localhost:5601) server in local,
then run the logstash server with a predefined logstash.conf file

now run the spring boot application.

To check logs in kibana,
Create an index in management section(only once, for first time)
Go in discover section and filter the logs based on the index name.
