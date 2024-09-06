## 演示

启动 zookeeper 

```bash
docker run -d -p 2181:2181 --name some-zookeeper --restart always zookeeper
```

启动服务提供者

```java
ProviderApplication
```

启动服务消费者

```java
ConsumerApplication
```

