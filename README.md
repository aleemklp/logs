This project peforms the log analytics using the ELK stacks by retrieving logs from two applciations sources Tomcat and Ngnix using the Filebeat

STEP 1 - SETUP Docker Elastic Kibanaa

cd docker-elk-nginx-tomcat-filebeat

docker-compose up -d

gets you elasticsearch running on localhost:9200 and kibana on localhost: 5601
