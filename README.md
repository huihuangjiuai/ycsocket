# ycsocket
基于 swoole 和 ycdatabase 的 websocket 框架

环境：
PHP7+
ycdatabase
swoole

我写游戏后端的时候写的

客户端是一个聊天窗口

支持Redis 协程线程池，源码位于 system/RedisPool，支持失败断开重连

支持 MySQL 协程连接池， 源码位于 system/MySQLPool 
