Running RabbitMQ in a docker container.
1. docker pull rabbitmq:3-management
2. docker run -d -p 15672:15672 -p 5672:5672 --name rabbit-test-for-medium rabbitmq:3-management
