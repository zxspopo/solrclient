# solrclient
a solrclient based upon solrj.基于消息总线，完成索引的更新删除操作。
#项目结构
- client
    
    客户端调用，提供基础查询。更新、删除索引的操作。
- server
    
    作为服务端，监听消息总线，消息驱动更新或者删除索引。
