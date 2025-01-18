# Go RabbitMQ Examples

## Run RabbitMQ with Docker

```bash
docker run -d --hostname rabbitmq -p 5672:5672 -p 15672:15672 --name rabbitmq rabbitmq:4.0.5-management-alpine
```
