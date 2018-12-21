# HazelcastTree
Hazelcast技术研究


<pre>
Hazelcast
 
         hazelcast其中一个很重要的应用就是可以将多个应用服务器组成一个分布式环境的应
     用，形成一个cluster。这个cluster可以选举出一个master来对外工作。而cluster中的各
     台服务器之间有数据同步机制和数据备份机制，来避免因为单个节点挂掉而导致数据丢失
     和cluster的失效。数据存储在分布式内存中，hazelcast可以保证数据在各个节点的均匀
     分布，可以增加节点和减少节点，而这个过程中，hazelcast会自动迁移数据，来保证数据的高可用。

        Hazelcast 提供了 Map、Queue、MultiMap、Set、List、Semaphore、Atomic 等接口的
     分布式实现；提供了基于Topic 实现的消息队列或订阅\发布模式；提供了分布式id生成
     器（IdGenerator）；提供了分布式事件驱动（Distributed Events）；提供了分布
     式计算（Distributed Computing）；提供了分布式查询（Distributed Query）。总的来
     说在独立jvm经常使用数据结果或模型 Hazelcast 都提供了分布式集群的实现。

        “分布式”、“集群服务”、“网格式内存数据”、“分布式缓存“、“弹性可伸缩服务”
</pre>