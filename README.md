```
java -jar zipkin.jar --server.port=8402 --zipkin.storage.type=mysql --zipkin.storage.mysql.db=febs_cloud_base --zipkin.storage.mysql.username=root --zipkin.storage.mysql.password=root --zipkin.storage.mysql.host=localhost --zipkin.storage.mysql.port=3306 --zipkin.collector.rabbitmq.addresses=localhost:5672 --zipkin.collector.rabbitmq.username=febs --zipkin.collector.rabbitmq.password=123456
```

```
启动nacos cd nacos/bin/
./startup.cmd -m standalone
```

```
各个镜像启动
/febs/febs-cloud
/febs/elk
 docker-compose up -d
```
