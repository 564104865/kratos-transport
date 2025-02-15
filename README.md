# kratos-transport

把消息队列、任务队列，以及Websocket等网络协议实现为微服务框架[Kratos](https://go-kratos.dev/docs/) 的`transport.Server`。

在使用的时候,可以调用`kratos.Server()`方法，将之注册成为一个`Server`。

## 支持的服务（Server）

### 消息队列

- [RabbitMQ](https://www.rabbitmq.com/)
- [Kafka](https://kafka.apache.org/)
- [RocketMQ](https://rocketmq.apache.org/)
- [ActiveMQ](http://activemq.apache.org)
- [Apollo](http://activemq.apache.org/apollo)
- [Pulsar](https://pulsar.apache.org/)
- [NATS](https://nats.io/)
- [NSQ](https://nsq.io/)
- [Redis](https://redis.io/)
- [MQTT](https://mqtt.org/)
- [STOMP](https://stomp.github.io/)
- [AMQP](https://www.amqp.org/)

### RPC

- [Thrift](https://thrift.apache.org/)
- [GraphQL](https://graphql.org/)

### 任务队列

- [Asynq](https://github.com/hibiken/asynq)
- [Machinery](https://github.com/RichardKnop/machinery)

### 网络协议

- [WebSocket](https://zh.wikipedia.org/zh-hant/WebSocket)
- [HTTP3](https://www.chromium.org/quic/)
- [WebTransport](https://web.dev/webtransport/)

## 支持的消息代理（Broker）

- [RabbitMQ](https://www.rabbitmq.com/)
- [Kafka](https://kafka.apache.org/)
- [RocketMQ](https://rocketmq.apache.org/)
- [ActiveMQ](http://activemq.apache.org)
- [Apollo](http://activemq.apache.org/apollo)
- [Pulsar](https://pulsar.apache.org/)
- [NATS](https://nats.io/)
- [NSQ](https://nsq.io/)
- [Redis](https://redis.io/)
- [MQTT](https://mqtt.org/)
- [STOMP](https://stomp.github.io/)
- [AMQP](https://www.amqp.org/)

## 应用示例

- [kratos-chatroom](https://github.com/tx7do/kratos-chatroom) 一个简单的Websocket聊天室的示例
- [kratos-cqrs](https://github.com/tx7do/kratos-cqrs) 一个CQRS架构模式的示例
- [kratos-realtimemap](https://github.com/tx7do/kratos-realtimemap) 一个物联网的公共交通实时显示地图的示例

以上示例程序在官方的[示例代码库](https://github.com/go-kratos/examples)中也可以找到。
