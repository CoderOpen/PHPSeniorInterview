redis是非关系型数据库，常用于应用于数据缓存，减轻后端数据库压力
* Q: redis常用的基本数据类型、常用命令、使用场景<br>
   * 字符串类型 常用于k，v简单键值对缓存，set get
   * list类型 可以用于简单的队列处理， push压入队列，pop出队列， bpop阻塞式出队列
   * 有序集合 
   * 无序集合
   * hash类型
   * 位图
   * 布隆过滤器
   * stream
* Q: redis管道是什么，有什么作用 <br>
* Q: redis事务有什么特点和使用场景 <br>
* Q：redis实现队列有哪些方式，优缺点 <br>
* Q: redis为什么这么快？<br>
* Q: redis和memcache的区别和各自使用场景 <br>
* Q: redis线程模型是怎么样的，redis6为啥引入多线程 <br>
* Q: redis持久化的两种方式及区别 <br>
* Q: redis过期删除模式 <br>
* Q: redis内存满了自动缓存淘汰，淘汰策略有哪些 <br>
* Q: redis如何配置淘汰策略<br>
* Q: LRU和LFU算法的区别<br>
* Q: 缓存更新策略有哪些缓存数据一致性问题怎么解决<br>
* Q: redis 大key问题是什么，怎么查找，怎么避免<br>
* Q: 缓存雪崩、击穿、穿透有什么区别，怎么避免，怎么解决<br>
* Q: redis如何实现相对靠谱的分布式锁<br>
* Q: redis集群的三种方式，各有什么优缺点<br>
* Q: redis cluster的实现原理<br>
* Q：哈希一致性原理是什么，解决了什么问题<br>
* Q：简单描述下redis数据类型对应的数据结构实现<br>