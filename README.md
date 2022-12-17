# Docker-Compose
Elastic-Stack :
Here is an example Docker Compose file that you can use to set up the Elastic Stack (Elasticsearch, Logstash, and Kibana) with Docker.

This Docker Compose file creates three containers: one for Elasticsearch, one for Logstash, and one for Kibana. The Elasticsearch container stores data in a persistent volume called "elasticsearch-data", which is defined at the bottom of the file. The Logstash container uses a configuration file called "logstash.conf", which you should place in the same directory as the Docker Compose file. The Kibana container is exposed on port 5601, which you can use to access the Kibana UI.

To use this Docker Compose file, make sure you have Docker and Docker Compose installed on your system, then save the file as "docker-compose.yml" and run the following command:

