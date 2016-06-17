# Docker ActiveMQ

Docker container to ActiveMQ Message Broker

## Pull image
```bash
docker pull andrelugomes/docker-activemq
```

## Run
```bash
docker run --name activemq -d -p 61616:61616 -p 8161:8161 andrelugomes/docker-activemq:5.13.3
```

## Tests
http://localhost:8161/admin/index.jsp
