# Introduction

[Paxos made simple](http://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

[Leslie Lamport](http://www.lamport.org/)

[2013 ACM Turing Award](https://amturing.acm.org/award_winners/lamport_1205376.cfm)

[关于 Paxos 的历史](关于Paxos的历史.md)

# Summary

- [0 `Introduction`](README.md)
- [1 `Algorithm`](README.md)
  - [1.1 `CAP`理论](algorithm/CAP.md)
  - [1.2 `ZAB`协议](algorithm/ZAB协议.md)
  - [1.3 分布式锁](algorithm/分布式锁.md)
  - [1.4 `RAFT`算法](algorithm/raft-zh_cn.md)
  - [1.5 3 分钟理解`PAXOS`算法](algorithm/PAXOS.md)
  - [1.6 `The Art of Multiprocessor Programming, Revised Reprint`](algorithm/TAMP.md)
  - [1.7 `BFPRT`算法](algorithm/BFPRT.md)
  - [1.8 `FisherYates`洗牌算法](algorithm/FisherYates洗牌算法.md)
  - [1.9 `Dapper`笔记](algorithm/Dapper笔记.md)
  - [1.10 算法概论](algorithm/算法概论.md)
  - [1.11 蓄水池抽样](algorithm/蓄水池抽样.md)
  - [1.12 哲学家就餐](algorithm/哲学家就餐.md)
  - [1.13 拜占庭将军问题](algorithm/拜占庭将军问题.md)
  - [1.14 分布式系统下的时间、时钟和事件次序](algorithm/分布式系统下的时间、时钟和事件次序.md)
  - [1.15 Zab 与 Raft](algorithm/Zab与Raft.md)
  - [1.16 算法之道](algorithm/算法之道.md)
- [2 Java](README.md)
  - [2.1 AQS 的独占与共享](java/AQS的独占与共享.md)
  - [2.2 设计模式](java/设计模式23.md)
  - [2.3 `EffectiveJava`](java/EffectiveJava.md)
  - [2.4 `Java`学习笔记](java/Java学习笔记.md)
  - [2.5 `JDK`相关](java/JDK相关.md)
  - [2.6 阿里`Java`编码规范整理](java/AlibabaJavaCodingGuidelines.md)
  - [2.7 深入了解`Java`程序执行顺序](java/Java程序执行次序.md)
  - [2.8 `JDK`定时任务对比](java/JDK定时任务对比.md)
  - [2.9 `Tomcat`中应用加载两次](java/Tomcat中应用加载两次.md)
  - [2.10 动态代理](java/动态代理.md)
  - [2.11 `Cron`大乱斗](java/Cron大乱斗.md)
  - [2.12 Java 获取时间](java/Java获取时间.md)
  - [2.13 Java 编码规范](java/Java编码规范.md)
  - [2.14 Java 知识点](java/Java知识点.md)
  - [2.15 Safe Publication and Safe Initialization in Java](java/Safe-Publication-and-Safe-Initialization-in-Java.md)
  - [2.16 `ThreadLocal`解析](java/ThreadLocal解析.md)
  - [2.17 JUC 解析](java/JUC解析.md)
  - [2.18 码农翻身整理](java/码农翻身整理.md)
  - [2.19 序列化与 JSON](java/序列化与JSON.md)
  - [2.20 Java 中的位运算](java/Java中的位运算.md)
  - [2.21 Java 的 assert 关键字](java/Java的assert关键字.md)
  - [2.22 Object 的方法](java/Object的方法.md)
  - [2.23 位操作的魔法](java/位操作的魔法.md)
  - [2.24 Java 中的多继承](java/Java中的多继承.md)
  - [2.25 tomcat 的启停脚本逻辑](java/tomcat的启停脚本逻辑.md)
  - [2.26 keytool 的使用](java/keytool的使用.md)
  - [2.27 Java 解惑](java/Java解惑.md)
  - [2.28 Java 线程状态](java/Java线程状态.md)
- [3 `SpringBoot`](README.md)
  - [3.1 `SpringBoot`的`pom.xml`](springboot/SpringBoot-pom-xml.md)
  - [3.2 `SpringBoot`的注解](springboot/SpringBoot注解.md)
  - [3.3 重新定义`SpringCloud`实战笔记](springboot/重新定义SpringCloud实战.md)
  - [3.4 `SpringBoot`自定义注解](springboot/自定义注解.md)
  - [3.5 `Hystrix+Turbine`](springboot/Hystrix+Turbine.md)
  - [3.6 SpringBoot 自动装配原理](springboot/SpringBoot自动装配原理.md)
  - [3.7 `SpringBoot`排错](springboot/SpringBoot排错.md)
  - [3.8 `SpringBoot`排雷现场](springboot/SpringBoot排雷现场.md)
  - [3.9 `SpringBoot`释疑](springboot/SpringBoot释疑.md)
  - [3.10 `SpringBoot`引入`log4j`的配置](springboot/SpringBoot引入log4j的配置.md)
  - [3.11 `SpringBoot`启动脚本](springboot/SpringBoot启动脚本.md)
  - [3.12 `SpringBoot`定时任务](springboot/SpringBoot定时任务.md)
  - [3.13 `SpringBoot`初始化任务](springboot/SpringBoot初始化任务.md)
  - [3.14 `SpringBootRedis`](springboot/SpringBootRedis.md)
  - [3.15 `SpringBootRabbitMQ`](springboot/SpringBootRabbitMQ.md)
  - [3.16 关于 Springboot 配置文件的设置](springboot/关于Springboot配置文件的设置.md)
  - [3.17 客户端配置更新](springboot/客户端配置更新.md)
  - [3.18 `SpringBoot`配置优先级](springboot/SpringBoot配置优先级.md)
  - [3.19 读取 SpringBoot 项目内的文件](springboot/读取SpringBoot项目内的文件.md)
  - [3.20 读取 x-www-form-urlencoded 类型的数据](springboot/读取x-www-form-urlencoded类型的数据.md)
  - [3.21 如何实现一个 starter](springboot/如何实现一个starter.md)
  - [3.22 springboot的版本变更记录](Spring/springboot的版本变更记录.md)
- [4 `RabbitMQ`](README.md)
  - [4.1 `RabbitMQ`相关](rabbitmq/RabbitMQ相关.md)
  - [4.2 `RabbitMQ`四种发送方式区别](rabbitmq/RabbitMQ四种发送方式区别.md)
  - [4.3 `RabbitMQ`安装全记录](rabbitmq/RabbitMQ安装全记录.md)
  - [4.4 `RabbitMQ`多地址连接](rabbitmq/RabbitMQ多地址连接.md)
  - [4.5 `RabbitMQConsumer`源码解析](rabbitmq/RabbitMQConsumer源码解析.md)
  - [4.6 `AMQP`协议](rabbitmq/AMQP协议.md)
  - [4.7 消息中间件选型图解](rabbitmq/消息中间件选型图解.md)
  - [4.8 `RabbitMQ`消息存储](rabbitmq/RabbitMQ消息存储.md)
  - [4.9 RabbitMQ 延时队列](rabbitmq/RabbitMQ延时队列.md)
  - [4.10 RabbitMQ 温故知新](rabbitmq/RabbitMQ温故知新.md)
- [5 `Shell`](README.md)
  - [5.1 免密登陆](shell/免密登陆.md)
  - [5.2 `iptables`命令](shell/iptables命令.md)
  - [5.3 `scp`命令](shell/scp命令.md)
  - [5.4 `shell`特殊变量的含义](shell/shell特殊变量的含义.md)
  - [5.5 `TCP`最大连接数](shell/TCP最大连接数.md)
  - [5.6 `Linux`命令整理](shell/Linux命令整理.md)
  - [5.7 常用 Linux 命令](shell/常用Linux命令.md)
  - [5.8 SpringBoot 启动脚本](shell/启动脚本.md)
  - [5.9 Linux 性能优化](shell/Linux性能优化.md)
  - [5.10 常用的 kill 信号](shell/常用的kill信号.md)
- [6 `ZooKeeper`](README.md)
  - [6.1 `ZooKeeper`集群安装](zookeeper/ZooKeeper集群安装.md)
  - [6.2 `ZooKeeper`权限控制](zookeeper/ZooKeeper权限控制.md)
  - [6.3 `ZooKeeperWatcher`](zookeeper/ZooKeeperWatcher.md)
  - [6.4 `ZooKeeper`连接](zookeeper/ZooKeeper连接.md)
  - [6.5 `ZooKeeper`临时节点之坑](zookeeper/ZooKeeper临时节点之坑.md)
  - [6.6 关于 ZK 的一些疑问](zookeeper/关于ZK的一些疑问.md)
- [7 `Pic`](README.md)
  - [7.1 `Java`相关](pic/Java相关.md)
  - [7.2 `JSON`语法](pic/JSON语法.md)
  - [7.3 其他](pic/其他.md)
- [8 `Scheduler`](README.md)
  - [8.1 定时任务调度框架整理](scheduler/定时任务调度框架整理.md)
  - [8.2 `TBSchedule`](scheduler/TBSchedule.md)
  - [8.3 `Onlinetask-Scheduler`](scheduler/Onlinetask-Scheduler.md)
  - [8.4 调度器负载均衡算法](scheduler/调度器负载均衡算法.md)
  - [8.5 有向无环图检测算法](scheduler/有向无环图检测算法.md)
  - [8.6 任务调度](scheduler/任务调度.md)
  - [8.7 XXL-JOB](scheduler/XXL-JOB.md)
- [9 `Redis`](README.md)
  - [9.1 缓存更新策略](redis/缓存更新策略.md)
  - [9.2 `Redis`集群搭建](redis/Redis集群搭建.md)
  - [9.3 Redis 深度历险](redis/Redis深度历险.md)
  - [9.4 Redis 与 IO 多路复用](redis/Redis与IO多路复用.md)
- [10 `JSR`](README.md)
  - [10.1 `Java-Servlet-4.0`阅读笔记](JSR/JSR-369-Java-Servlet-4.0阅读笔记.md)
  - [10.2 `JSR133`-内存模型](JSR/JSR133-内存模型.md)
  - [10.3 Java 虚拟机规范笔记](JSR/Java虚拟机规范笔记.md)
- [11 `MongoDB`](README.md)
  - [11.1`MongoDB`集群与分片](mongodb/MongoDB集群与分片.md)
- [12 `Nacos`](README.md)
  - [12.1 `Nacos`简介](nacos/Nacos简介.md)
  - [12.2 Nacos 升级至 2.0.2 踩坑全记录](nacos/Nacos升级至2.0.2踩坑全记录.md)
  - [12.3 Nacos 原理](nacos/Nacos原理.md)
  - [12.4 Nacos问题答疑](nacos/Nacos问题答疑.md)
  - [12.5 Nacos_PPT](nacos/Nacos_PPT.md)
- [13 `Eureka`](README.md)
  - [13.1 `Eureka`简介](eureka/Eureka简介.md)
  - [13.2 `Eureka`解析](eureka/Eureka解析.md)
- [14 Code](README.md)
  - [14.1 线程安全的`SDF`](code/线程安全的SDF.md)
  - [14.2 获取本机`IP`](code/获取本机IP.md)
  - [14.3 网络探测：`ping`与`telnet`](code/网络探测：ping与telnet.md)
  - [14.4 令牌桶](code/令牌桶.md)
  - [14.5 Spring 上下文](code/Spring上下文.md)
  - [14.6 请求参数与耗时](code/请求参数与耗时.md)
- [15 Database](README.md)
  - [15.1 AnOutlineforaBookonInnoDB](database/AnOutlineforaBookonInnoDB.md)
  - [15.2 MySQL 建表关键字说明](database/MySQL建表关键字说明.md)
  - [15.3 MySQL 问题整理](database/MySQL问题整理.md)
  - [15.4 字典表设计](database/字典表设计.md)
  - [15.5 树形结构](database/树形结构.md)
  - [15.6 理解 MySQL](database/理解MySQL.md)
  - [15.7 密码加盐](database/密码加盐.md)
  - [15.8 对 NOT NULL 的理解](database/对NOT_NULL的理解.md)
  - [15.9 为什么 DB 连接管理一般不采用 IO 多路复用](database/为什么DB连接管理一般不采用IO多路复用.md)
  - [15.10 MySQL 中事务的实现](database/MySQL中事务的实现.md)
  - [15.11 数据库中为什么不推荐使用外键约束](database/数据库中为什么不推荐使用外键约束.md)
  - [15.12 分布式事务](database/分布式事务.md)
  - [15.13 时间戳检测死锁](database/时间戳检测死锁.md)
  - [15.14 B+树和跳表](database/B+树和跳表.md)
  - [15.15 NULL 值不应该存储的原因](database/NULL值不应该存储的原因.md)
  - [15.16 数据库访问缓慢排查](database/数据库访问缓慢排查.md)
  - [15.17 InnoDB 与 MyISAM](database/InnoDB与MyISAM.md)
- [16 OS](README.md)
  - [16.1 windows 相关](OS/windows相关.md)
  - [16.2 Monitor](OS/Monitor.md)
  - [16.3 操作系统导论](OS/操作系统导论.md)
  - [16.4 计算机组成原理](OS/计算机组成原理.md)
  - [16.5 文件描述符](OS/文件描述符.md)
  - [16.6 零拷贝](OS/零拷贝.md)
  - [16.7 select_poll_epoll](OS/select_poll_epoll.md)
  - [16.8 容器、Docker 和 K8S](OS/容器、Docker和K8S.md)
  - [16.9 CpuUsage](OS/CpuUsage.md)
  - [16.10 Linux知识点](OS/Linux知识点.md)
- [17 Network](README.md)
  - [17.1 jsch 的使用](network/jsch的使用.md)
  - [17.2 会话管理](network/会话管理.md)
  - [17.3 长短连接](network/长短连接.md)
  - [17.4 SSL 工作原理](network/SSL工作原理.md)
  - [17.5 CORS+CSRF+XSS](network/CORS+CSRF+XSS.md)
  - [17.6 BIO+NIO+AIO](network/BIO+NIO+AIO.md)
  - [17.7 网络协议](network/网络协议.md)
  - [17.8 TIME_WAIT 与 CLOSE_WAIT](network/TIME_WAIT与CLOSE_WAIT.md)
- [18 JVM](README.md)
  - [18.1 CMS 的重新标记做了啥](JVM/CMS的重新标记做了啥.md)
  - [18.2 GC 为什么分代](JVM/GC为什么分代.md)
  - [18.3 Java 虚拟机](JVM/Java虚拟机.md)
  - [18.4 JVM 梳理](JVM/JVM梳理.md)
  - [18.5 ZGC](JVM/ZGC.md)
  - [18.6 从实际案例聊聊 Java 应用的 GC 优化](JVM/从实际案例聊聊Java应用的GC优化.md)
  - [18.7 引用计数与可达性](JVM/引用计数与可达性.md)
  - [18.8 RememberedSet 与卡表](JVM/RememberedSet与卡表.md)
  - [18.9 CMS 为什么没有采用标记-整理算法来实现](JVM/CMS为什么没有采用标记-整理算法来实现.md)
  - [18.10 MajorGC 与 FullGC](JVM/MajorGC与FullGC.md)
  - [18.11 GC 日志中新生代的不同名字](JVM/GC日志中新生代的不同名字.md)
  - [18.12 三色标记算法](JVM/三色标记算法.md)
  - [18.13 G1 的参数设置](JVM/G1的参数设置.md)
  - [18.14 GC 日志分析](JVM/GC日志分析.md)
  - [18.15 ConcurrentModeFailure](JVM/ConcurrentModeFailure.md)
- [19 Architecture](README.md)
  - [19.1 RPC 异步调用](architecture/RPC异步调用.md)
  - [19.2 单点 VS 集群 VS 分布式](architecture/单点VS集群VS分布式.md)
  - [19.3 负载均衡与高可用](architecture/负载均衡与高可用.md)
  - [19.4 权限管理系统](architecture/权限管理系统.md)
  - [19.5 为什么这么设计整理](architecture/为什么这么设计整理.md)
  - [19.6 云原生](architecture/云原生.md)
  - [19.7 如何秒杀](architecture/如何秒杀.md)
  - [19.8 内存和缓存一致性基础](architecture/内存和缓存一致性基础.md)
  - [19.9 共享内存同步](architecture/共享内存同步.md)
- [20 HTTP](README.md)
  - [20.1 cookie+session](HTTP/cookie+session.md)
  - [20.2 NginxApache 和 Tomcat](HTTP/NginxApache和Tomcat.md)
  - [20.3 origin](HTTP/origin.md)
  - [20.4 Referer](HTTP/Referer.md)
  - [20.5 SO_REUSEPORT](HTTP/SO_REUSEPORT.md)
  - [20.6 TLS](HTTP/TLS.md)
  - [20.7 AK_SK](HTTP/AK_SK.md)
- [21 Spring](README.md)
  - [21.1 SpringBean 的生命周期和作用域](Spring/SpringBean的生命周期和作用域.md)
  - [21.2 SpringSession 原理](Spring/SpringSession原理.md)
  - [21.3 Spring 的事务传播](Spring/Spring的事务传播.md)
  - [21.4 Spring 的循环依赖及其解决](Spring/Spring的循环依赖及其解决.md)
  - [21.5 UndeclaredThrowableException](Spring/UndeclaredThrowableException.md)
  - [21.6 过滤器与拦截器](Spring/过滤器与拦截器.md)
  - [21.7 EL 表达式](Spring/EL表达式.md)
  - [21.8 提前读取配置的属性](Spring/提前读取配置的属性.md)
  - [21.9 yml_and_property](Spring/yml_and_property.md)
  - [21.10 @PostConstruct注解](Spring/@PostConstruct注解.md)
  - [21.11 构造函数注入](Spring/构造函数注入.md)
- [22 Netty](README.md)
  - [22.1 Netty 的线程模型](Spring/Netty的线程模型.md)
  - [22.2 Netty 解决 epoll 空转问题](Spring/Netty解决epoll空转问题.md)
- [23 Solution](README.md)
  - [23.1 Java 中的源码](solution/Java中的源码.md)
  - [23.2 背包问题](solution/背包问题.md)
  - [23.3 并查集](solution/并查集.md)
  - [23.4 堆排](solution/堆排.md)
  - [23.5 二叉树的非递归遍历与重建](solution/二叉树的非递归遍历与重建.md)
  - [23.6 二分查找模板](solution/二分查找模板.md)
  - [23.7 股票问题](solution/股票问题.md)
  - [23.8 归并排序](solution/归并排序.md)
  - [23.9 快排](solution/快排.md)
  - [23.10 马拉车算法](solution/马拉车算法.md)
  - [23.11 排列与组合](solution/排列与组合.md)
  - [23.12 排列组合子集进阶](solution/排列组合子集进阶.md)
  - [23.13 扔鸡蛋问题](solution/扔鸡蛋问题.md)
  - [23.14 搜索](solution/搜索.md)
  - [23.15 子串匹配问题](solution/子串匹配问题.md)
  - [23.16 正则](solution/正则.md)
  - [23.17 滑动窗口](solution/滑动窗口.md)
  - [23.18 字符串排序](solution/字符串排序.md)
  - [23.19 二分图](solution/二分图.md)
  - [23.20 连通分量](solution/连通分量.md)
  - [23.21 强连通分量](solution/强连通分量.md)
  - [23.22 拓扑排序](solution/拓扑排序.md)
  - [23.23 无向图的环](solution/无向图的环.md)
  - [23.24 红黑树](solution/红黑树.md)
  - [23.25 单词查找树](solution/单词查找树.md)
  - [23.26 最短路径](solution/最短路径.md)
- [24 go](README.md)
  - [24.1 Aeron](go/Aeron.md)
  - [24.2 THE WAY TO GO](go/THE_WAY_TO_GO.md)
  - [24.3 K8S](go/K8S.md)
  - [24.4 JS](go/JS.md)
- [25 tools](README.md)
  - [25.1 Async-profile](tools/Async-profiler.md)
  - [25.2 Prometheus](tools/Prometheus.md)
  - [25.3 skywalking](tools/skywalking.md)
  - [25.4 Conprof](tools/Conprof.md)
  - [25.5 Exemplars](tools/Exemplars.md)
  - [25.6 AsyncGetCallTrace](tools/AsyncGetCallTrace.md)
  - [25.7 反应式编程](tools/反应式编程.md)
  - [25.8 sdkman](tools/sdkman.md)
- [`Other`](README.md)
  - [1 `ActiveMQ`简介](other/ActiveMQ简介.md)
  - [2 `Atom`安装](other/Atom安装.md)
  - [3 `GitBook`](other/GitBook.md)
  - [4 `MarkDown`](other/MD语法.md)
  - [5 `Nginx`](other/Nginx安装.md)
  - [6 OTP 动态令牌](other/OTP动态令牌.md)
  - [7 `SublimeText3`快捷键精华版](other/SublimeText3快捷键精华版.md)
  - [8 `Webdis`安装](other/webdis安装.md)
  - [9 `Zabbix`](other/zabbix.md)
  - [10 安装`ES-head`](other/安装ES-head.md)
  - [11 快速熟悉新项目](other/快速熟悉新项目.md)
  - [12 思维导图](other/思维导图.md)
  - [13 思考的乐趣](other/思考的乐趣.md)
  - [14 资源汇总](other/资源汇总.md)
  - [15 git 常用操作](other/git常用操作.md)
  - [16 关键对话](other/关键对话.md)
  - [17 VSCode](other/VSCode.md)
  - [18 Maven 相关](other/Maven相关.md)
  - [19 LogBack 相关](other/LogBack相关.md)
  - [20 OAuth2.0](other/OAuth2.0.md)
  - [21 packaging 为 pom 标签的用法](other/packaging为pom标签的用法.md)
  - [22 资源待读](other/ToRead.md)
