# basic-mq-app

```bash
docker run -it --rm --name rabbitmq -p 5672:5672 rabbitmq
```
sender
```bash
go run cmd/server/server.go
```
receiver
```bash
go run cmd/client/client.go
```

