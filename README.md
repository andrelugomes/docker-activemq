# Docker ActiveMQ

Docker container to ActiveMQ Message Broker

## Pull image
```bash
docker pull andrelugomes/docker-activemq:5.12.0
```

## Run
```bash
docker run -d -p 61616:61616 -p 8161:8161 andrelugomes/docker-activemq:5.12.0
```

## Tests
http://localhost:8161/admin/index.jsp
