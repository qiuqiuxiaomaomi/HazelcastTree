# HazelcastTree
Hazelcast技术研究


<pre>
Hazelcast
 
         hazelcast其中一个很重要的应用就是可以将多个应用服务器组成一个分布式环境的应
     用，形成一个cluster。这个cluster可以选举出一个master来对外工作。而cluster中的各
     台服务器之间有数据同步机制和数据备份机制，来避免因为单个节点挂掉而导致数据丢失
     和cluster的失效。数据存储在分布式内存中，hazelcast可以保证数据在各个节点的均匀
     分布，可以增加节点和减少节点，而这个过程中，hazelcast会自动迁移数据，来保证数据的高可用
</pre>