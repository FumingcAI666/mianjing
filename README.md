# 2019秋招集合

阿里-后台开发-电话40min

1、自我介绍
2、怎么解决activemq幂等问题
3、zookeeper分布式缓存怎么解决
4、redis的过期策略
（FIFO ，first in first out ，最先进入缓存的数据在缓存空间不够情况下(超出最大元素限制时)会被首先清理出去
LFU ， Less Frequently Used ，一直以来最少被使用的元素会被被清理掉。这就要求缓存的元素有一个hit 属性，在缓存空间不够得情况下,hit 值最小的将会被清出缓存。
LRU ，Least Recently Used ，最近最少使用的，缓存的元素有一个时间戳，当缓存容量满了，而又需要腾出地方来缓存新的元素的时候，那么现有缓存元素中时间戳离当前时间最远的元素将被清出缓存。）
5、Linux进程间的通信方式
6、进程和线程的区别
7、死锁产生的条件
8、左连接 右连接 内连接
9、数据库索引原理
10、b树b+区别



阿里-后台开发-视频40min

1、自我介绍
2、用过什么分布式框架？
3、redis怎么保证数据一致性？
4、了解乐观锁和悲观锁吗，乐观锁在代码中怎么实现？
5、SQL慢查询了解吗？
6、用过SOA吗？
7、介绍一下HashMap，Hashmap中put扩容1.8之后怎么优化的？
8、static对象在内存中怎么存放？
9、OOM遇到过吗，怎么解决的？
10、Effective  Java看过吗 说一下你印象深的三个地方
11、线程池的组成部分、常用线程池？
12、十万个数据查最小的10个数
13、N个赛车如何同时启动



小米一面-后台开发-牛客面试间-60mian
面试官：自我介绍
进入正题
1、实习阶段完成的项目
2、幂等性控制机制
3、ActiveMQ和RabbitMQ什么区别，RabbitMQ业务场景是什么，怎么选择消息队列
4、Redis数据结构，hash结构存储HashMap，在集群中key的存放
5、svn和git看你都用过，有什么不同
6、数据库常用的数据类型，float double有什么区别，decimal解决浮点型精度问题
7、MySQL索引（说了Innodb MyISAM的区别，存储结构B+树，B树）
8、乐观锁和悲观锁的场景和实现
9、什么是gc
10、tcp三次握手，http请求流程
11、常用那些设计模式，在什么场景下
12、常用的算法的时间复杂度
面试官点评：基础理论、原理及知识面广度可以，但是实际开发场景和教科书还是有一定区别，对细节处理或者可能是表达的不够准确不够好，比如MySQL没提联合索引最左匹配等必说的基础部分，设计模式实际实现不够具体



滴滴-后台开发-视频50min
做下自我介绍
你都做过什么，移动端开发有了解吗？后端,和微信开发，h5，安卓ios，泛前端都有了解吗？你以后的方向是什么？
1、启动两个线程A、B，如何让两个线程像ABABAB这样循环执行？（我围绕join说了下，面试官提醒循环会导致死锁，改口CyclicBarrier）
2、当前线程跑一亿条数据，如何中断线程，在执行run()中如何中断
3、先启动A线程再启动B线程，他们执行的流程是什么样的
4、线程池了解吗，你自己实现一个线程池（开始说核心线程数、最大线程数、饱和策略，存活时间、阻塞队列这类，面试官提醒抛开API自己实现一个单例的线城池，改口具体如何实现阻塞队列，ps:查了一下可以使用enum）
5、你对线程间同步如何理解的，什么情况下线程需要同步（说了synchronized，面试官提醒线程之间同步还是没反应过来，说了synchronized、jmm这些，实际上实现线程间同步可以通过Object的wait和notify，通过Condition的awiat和signal，通过一个阻塞队列，通过两个阻塞队列，通过SynchronousQueue ，通过线程池的Callback回调，通过同步辅助类CountDownLatch，通过同步辅助类CyclicBarrier）
6、在集合中删除所有偶数位置的数据（Iterator、for，不使用foreach）
结束，你还有什么要问我的吗



哈啰出行-后台开发-现场30min
自我介绍
项目难点，怎么解决的
频繁缓存穿透怎么解决
缓存数据类型
缓存同步机制
类加载机制
类的生命周期
JVM组成
分析操作数栈和局部变量表
堆，方法区1.7和1.8的区别
pc寄存器存储什么
你觉得你有什么优点，缺点
最近学什么

哈啰出行-后台开发-hr面-现场30min
自我介绍
学校经历
说一个在学校或者实习让你自豪的事
上一家公司给你多少，为什么要来这里
你最感兴趣的一个公司，为什么，怎么没去，网申了吗，面试了吗
你想去哈啰的哪个部门
能接受毕业前实习吗
说说你的优点缺点
职业规划
你有什么要问我的吗



去哪儿网-后台开发-现场50min
自我介绍
项目介绍
mq幂等性
dubbo发布，不停机发布
热部署和灰度发布
索引
gc算法
垃圾回收器
频繁gc的原因
算法：设计login方法（可能要考虑第三方登录，单点登录，权限控制）
算法：已知中后求先序
算法：两个链表，非环判断是否有交点
算法：判断一个字符串是否符合一定规则

