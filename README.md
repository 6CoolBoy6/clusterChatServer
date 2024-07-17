# clusterChatServer
该项目基于 Muduo 库实现了一个多线程、多 Reactor 模型的高并发聊天服务器，通过 Nginx 的 TCP 负载均衡模块分发客户端请求，并利用 Redis 的发布订阅功能同步服务器间的消息，从而构建了一个高性能的集群聊天服务器。
