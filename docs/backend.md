

# 湖北大学瑞翼工坊后端培养方案

> 版本：1.0.1 
>
> 撰写：刘旭，方玉龙
>
> 审核：

## 面试要求

- 对计算机有强烈爱好的；

- 能独立解决问题的；

- 有基础编程能力的，对任意编程语言有实操经验的；

- 好奇心重、有探索心、自学能力强的；

  

## 培养目标

- 语言基础：熟练掌握Java/Go等其中一门开发语言，并了解语言的原理知识。
- 算法：了解基本数据结构，基本算法。
- 设计模式： 比较了解各种设计模式与其对应的场景。
- 操作系统： 对Linux操作系统有基本了解，包括常见Linux命令、内存管理、进程线程、堆栈等等，对常见IO模型有基本了解，包括阻塞、非阻塞、多路复用等常见模型；
- 网络：了解基本的网络协议，对TCP/UDP网络协议、HTTP/HTTPS、Socket、粘包拆包等原理有基本了解；
- 数据库： 熟练掌握对MySQL及SQL语言的编写，对MySQL的架构、事务、日志、隔离级别、主从复制有基本了解，
- 常用中间件：对缓冲中间件redis，消息中间件socketMQ，日志中间件Elasticsearch等其他中间件了解基本使用和底层原理。
- 微服务：了解对应语言的微服务框架(java：springcloud，go：micro)，及未来微服务的架构(istio,dapr)
- 其他要求：对Python、Shell等脚本语言有一定的了解，对docker、云计算、网络安全、测试、项目管理有基本的认知；



## 方向分流

后端开发分为两个主流方向，一边是Go开发，一边是Java开发

Go语言本身相比起Java来说，要更加的轻量级，语法简洁，且容易应对并发场景，许多大厂正慢慢向Go迁移；

但是Java的生态比较完善，市场使用率较高，目前市场岗位相对较多，且学校也有相关课程，更易于吸收使用；

同学可以按自己兴趣选一个方向进行针对性的学习

各方向具体要求如下

### Go

- 熟练掌握Go语法，能独立完成简单需求；
- 熟练掌握开发框架Gin，能独立开发类似学生管理系统之类的简单项目，并可以随着学习对该系统进行升级，例如引入缓存缓存，消息队列等。
- 对Slice、Channel、Map的底层原理有基本了解；
- 对GC、Goroutine调度、runtime有基本了解；
- 主要技术栈: web框架(gin)，orm框架(xorm)，微服务框架(micro)，rpc框架(grpc)



### Java

- 熟练掌握Java语法，能独立完成简单需求；
- 掌握开发框架SpringBoot，能独立开发类似学生管理系统之类的简单项目；
- 对Spring、SpringBoot基本原理与特性有基本了解；
- 对List、Set、Map的底层原理有基本了解；
- 对JVM、GC等基层原理有基本了解；
- 主要技术栈: web框架(springboot)，orm框架(Mybatis-plus)，微服务框架(springcloud)



## 学习路线

### **Go**

学习视频：《基础知识》https://www.bilibili.com/video/BV1Uq4y1Q7Jn

​					《gin》 https://www.bilibili.com/video/BV1bp4y1x7Th

​					《micro》 https://www.bilibili.com/video/BV1Ei4y1u7iw

​					 《grpc》 https://www.bilibili.com/video/BV1GE411A7kp

文档书籍：《Go语言中文文档》https://topgoer.com/

​					《Go预言圣经》https://yar999.gitbook.io/gopl-zh/

​					《Go语言学习之路》https://www.liwenzhou.com/posts/Go/golang-menu/



### **Java**

学习视频：  《基础知识》 https://www.bilibili.com/video/BV1Cv411372m 掌握基本语法就好

​					《springboot》 https://www.bilibili.com/video/BV1Lq4y1J77x

​					《springboot+mybatis》https://www.bilibili.com/video/BV1NJ411q7zD

​					《springcloud》https://www.bilibili.com/video/BV1mt41127Rj

​					 《内部资料：springboot》 https://www.bilibili.com/video/BV12j411f7k6



### **MySQL**

菜鸟教程：https://www.runoob.com/mysql/mysql-tutorial.html

极客时间（收费）：https://time.geekbang.org/column/intro/100020801



### **Redis**

菜鸟教程：https://www.runoob.com/redis/redis-tutorial.html

极客时间（收费）：https://time.geekbang.org/column/intro/100056701



### **ElasticSearch**

b站： https://www.bilibili.com/video/BV1hh411D7sb



### **Docker**

菜鸟教程：https://www.runoob.com/docker/docker-tutorial.html

b站：https://www.bilibili.com/video/BV1og4y1q7M4

内部课程： https://www.bilibili.com/video/BV13E411x7ZV



### **基础部分**

以项目实战为主，开发中学习，按照培养目标逐个击破