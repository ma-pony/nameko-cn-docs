# nameko是什么

Nameko是一个Python的微服务框架，开箱即用，他并不是一个web框架，如果你想搭建一个web应用程序，那你应该使用fastapi,django之类的框架

他默认支持：

* 基于AMQP协议的RPC
* 基于AMQP的异步事件（发布-订阅）
* 简单的HTTP Service\(GET, POST等\)
* Websocket RPC和订阅

同时他的可扩展性非常高，你可以定义自己的服务传输协议和依赖性，例如nameko-grpc等

{% embed url="https://github.com/fkromer/awesome-nameko" %}

在awesome-nameko项目中你可以找到非常多的扩展

Nameko强烈鼓励依赖注入模式



