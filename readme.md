docker container rm rabbitmq-mq 
docker container run  --name rabbitmq-mq -p 5672:5672 -p 15672:15672  tournament-mq