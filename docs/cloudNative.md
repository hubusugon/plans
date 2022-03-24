# 湖北大学瑞翼工坊云原生开发培养目标

> 版本：1.0.1 
>
> 撰写：方玉龙,陆麟趾
>
> 审核：

## 能力要求

> 精通：能够使用某种技术，并有较多的实际项目经验，且能掌握全部原理和实现细节 熟练掌握：能够使用某种技术，并有较多的实际项目经验，且能掌握核心原理 掌握：能够使用某种技术，并有较多的实际项目经验 熟悉：能够使用某种技术，并有较少的实际项目经验 了解：能够使用某种技术，知道核心知识点

1. 语言基础：熟练掌握Go语言，掌握Go语言特点,包管理方式等。
2. 计算机基础：熟练掌握操作系统原理，对线程调度，存储，内存，CPU模块需要深入了解，并了解内存，CPU虚拟化的相关原理(cgroups技术)有较多了解。
3. 网络：掌握常用的网络协议(TCP、UDP、HTTP、HTTPS),也需要对二层和三层网络有较多的理解。
4. 工程基础能力： 掌握Git等常见的团队协作工具，能熟悉使用Tekton，jenkins等cicd构建工具平台了解云原生时代的开发模式。
5. 工程编码能力： 了解常见设计模式，非常熟悉观察者模式。对常见数据结构和算法需要了解，并了解分布式算法例如分布式一致性算法Raft。
6. 框架： 掌握gin框架
7. 云原生基础组建： 熟悉Docker，Kubernetes,jenkins,tekton,elk,Prometheus,istio等云原生基础组建的使用，对Docker和kubernetes需要熟悉原理深入了解
8. 团队协作：良好的沟通能力和团队协同能力；具有一定的项目管理经验，能够带领团队，完成项目开发。

## 学习路线

云原生最好开始了解微服务体系建议先学习了解一下(springcloud或micro)，因为与微服务中的服务发现，配置中心等概念用共通之处

### Docker

- 菜鸟教程：https://www.runoob.com/docker/docker-tutorial.html

  b站：https://www.bilibili.com/video/BV1og4y1q7M4

  内部课程： https://www.bilibili.com/video/BV13E411x7ZV

阶段性项目实践：可以使用Docker一键启动不同语言的环境，一键启动Mysql，Nginx等常用中间件

### Jenkins

- b站：https://www.bilibili.com/video/BV1GW411w7pn

阶段性项目实践：可以在jenkins上使用搭建各种流水线，并与docker相结合实现自动打包docker镜像的任务。



### Kubernetes

- 基础，尚硅谷：https://www.bilibili.com/video/BV1w4411y7Go   (比较难理解整个视频需要看两到三次)
- 内部课程： https://www.bilibili.com/video/BV13E411x7ZV
- 二次开发：https://www.bilibili.com/video/BV1NF411x7Qw

阶段性项目实践：能使用kubernetes搭建常见的服务，能开发简单的kubernetes控制器，能结合jenkins搭建k8s的cicd流水线

### Operator-sdk

- 基础: https://www.bilibili.com/video/BV1NF411x7Qw

阶段性项目实践：能对k8s进行二次开发，制作简单的控制器



### 网络

- 课程 趣谈网络协议(收费课程)：[https://time.geekbang.org/column/intro/100007101](https://gitee.com/link?target=https%3A%2F%2Ftime.geekbang.org%2Fcolumn%2Fintro%2F100007101)

一些博客文章

### 数据结构与算法

- 学习：大话数据结构、算法图解
- 刷题：Leetcode（分类刷）、《剑指Offer》

## 项目所需

### Git

- Pro Git 第二版
- 阮一峰的Git教程：[https://www.liaoxuefeng.com/wiki/896043488029600](https://gitee.com/link?target=https%3A%2F%2Fwww.liaoxuefeng.com%2Fwiki%2F896043488029600)

