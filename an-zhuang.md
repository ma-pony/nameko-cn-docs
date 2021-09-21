# 安装

 安装nameko

```text
$ pip install nameko
```

安装rabbitmq

```text
$ docker run -d --name rabbitmq --publish 5671:5671 --publish 5672:5672 --publish 25672:25672 --publish 15671:15671 --publish 15672:15672 -p 53160:53160/udp --hostname rabbit \
   --restart always --name rabbit rabbitmq:3.7.18-management
```

