# interview-solution 


[TOC]

# 快手

1. 类似Excel表，A....Z AA...AZ BA...BZ，分别对应数字0...25 26....51 52...77，类比做数字映射，给出一个字符串，求映射的结果.

   

2. mysql索引怎么建立，查询语句select * from T where a="a" and b="b" and c="c",与select * from T where a="a" and c="c" and b="b"执行有什么区别吗？建议索引遵循什么原则？

   

3. redis里有哪些数据结构，都用过什么？redis里zset怎么用，需要传什么参数？

4. java volatile干什么用的。public int incrment() { count++}，两个线程同时访问是否有问题，count如果用volatile修饰呢？

5. jvm里内存分配什么样的，分别用来干什么？

6. jvm的栈是做什么，为什么有堆又有栈，只使用堆可以吗？

7. redis分布式锁实现要注意什么？能写出分布式的加锁和释放锁的代码吗？如果是分布式可重入锁呢？如果有可重入度呢？

8. 分布式自增id怎么实现，如果用redis实现，怎么保证与数据库的一致性？

9. ArrayList，LinkedList有什么区别，分别什么时候使用？

10. HashMap，HashTable，ConcurrentHashMap有什么区别，说下HashMap实现，ConcurrentHashMap为什么使用分段锁，jdk 1.7 1.8版本有什么不同，怎么扩容的，CAS是具体怎么操作的？

11. CAS怎么实现的，为什么CAS就是原子操作？

12. 用哪些测试框架？测试用例怎么写的，平时写完一个程序或功能后怎么测试的？测试数据注意哪些？访问外部资源时怎么办？

13. 类加载顺序，一个java程序写完，到运行的整个过程。

# 

1. 数组如1 2 3 4 5 6 5 4 3 2 1，先升序，后降序，找出最大数字？

2. TCP的建立连接和断开连接的具体过程，为什么分别是三次和四次挥手？可以减少吗？

3. TCP/IP中可以重传某个seqId的包吗？

4. c++ static const 怎么初始化的？

5. 如果让你写memcpy，需要注意些什么？

   

