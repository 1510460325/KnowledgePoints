# 春招知识点准备  
## [Java基础](./docs/java/README.md)： 
* 集合容器以及底层实现原理  
* String类 
* 初始化顺序的执行顺序
* 接口和类的理解  
* 反射机制和内省机制  
* java的序列化  
* 伪共享问题
## [JVM相关知识点](./docs/jvm/README.md)
* java内存模型：工作内存和主内存
* java对象存储模型
* java内存结构及各个区域的作用
* 什么时候触发哪种类别的GC
* GC的算法
    * 新生代、老年代、永久代
* 类加载机制
    * 各个阶段（7个阶段）的工作流程
    * 双亲委派模式  
* JVM GC算法和垃圾收集器
## [多线程、锁](./docs/lock/README.md)
* 线程池
    * 使用好处
    * 实现原理（线程复用、管理线程）
    * 拒绝策略
* 竞态条件
* 检测线程是否拥有锁
* 锁分类
    * 悲观锁/乐观锁
    * 公平锁/非公平锁
    * 独享锁/共享锁
    * 自旋锁/自适应自旋锁
    * 偏向锁/轻量级锁/重量级锁
* volatile关键字
* synchronized关键字和Lock的使用区别
* synchronized锁升级
* AQS的实现原理
* 独占锁（ReentrantLock）的实现原理
* Condition的实现原理
* 读写锁（ReentrantReadWriteLock）的实现原理
* linkedBlockingQueue实现原理
* ConcurrentHashMap实现原理
* CountDownLatch闭锁(基于共享锁AQS)
* Semaphore（基于共享锁AQS）
* CyclicBarrier(lock实现)
## [ssm框架](./docs/framework/README.md)
* spring框架的理解
    * IOC和DI的原理和源码分析
    * AOP的实现原理
    * 事务的实现、传播行为
    * spring管理的bean的模式，默认原型
    * spring如何管理bean、bean的生命周期
* springMvc的理解
    * 接口地址和方法的映射过程
    * @ResponseBody的处理
    * @RequestMapping的处理
* Mybatis的理解
    * sql语句和方法的映射原理
    * \#｛｝ 和 \$｛｝的区别
* 拦截器、过滤器  
## [mysql（InnoDB）](./docs/mysql/README.md)
* 数据库ACID
* 事务的隔离级别
* 事务的传播行为
* 数据库锁
* 事务的实现原理
* 存储的物理结构和逻辑结构
* 数据类型及其区别
* 索引分类
* 索引实现原理（B+树）
* 自适应哈希
## [zookeeper相关知识点](./docs/zookeeper/README.md)
* 监听机制
* 节点读写的原子性
* 读写操作过程
* 选举过程
* zookeeper实现分布式锁
## [计算机网络](./docs/ComputerNet/README.md)
* 冯诺依曼体系结构
* OSI 7层模型
* TCP 5层模型
* tcp三次握手
* tcp四次挥手
* 流量控制和拥塞控制
* 滑动窗口协议
* http协议
* UDP协议