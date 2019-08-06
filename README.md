# springboot-kafka-consumer
springboot整合kafka当消息队列，zookeeper当注册中心

jdk:1.8, springboot:2.1.6, spring-kafka:2.2.7, 

kafka集群其中一个端口是192.168.137.130:9093
```
│  
├─.mvn
│  └─wrapper
│          maven-wrapper.jar
│          maven-wrapper.properties
│          MavenWrapperDownloader.java
│      
├─src
│  ├─main
│  │  ├─java
│  │  │  └─com
│  │  │      └─ssm
│  │  │          │  SpringBootKafkaConsumerApplication.java	//启动类
│  │  │          │  
│  │  │          └─consumer
│  │  │                  Consumer.java	//消费者容器类，也可以认为是接受消息的类	
│  │  │                  
│  │  └─resources
│  │      │  application.yml			//kafka的配置文件
│  │      │  
│  │      ├─static
│  │      └─templates
```
