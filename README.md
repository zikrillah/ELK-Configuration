<<<<<<< Updated upstream
# ELK-Configuration
This folder contain two file for ELK configuration
## access-log-nginx.conf
This file is snippe code from my nginx defaul config to log the user access
## my-logstash.conf
This file is logstash configuration, the input is from filebeat that send the nginx access and error log, in the filter configuration try to parsing the both files based on fileset names and make two index file on elastic based on fileset name