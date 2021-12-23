Redis 6.0 源码注释
-----------------

本项目是注释版的 Redis 6.0 源码，原始代码：https://github.com/redis/redis/tree/6.0.16

项目初衷是为了学习 Redis 6.0 新的特性以及进一步了解其内部实现而制作的


阅读顺序 & 源码文件简介
-----------------

| 序号 | 文件 | 简介 |
| ------------- | ------------- | ------------- |
| 1  | `sds.h`、`sds.c` | 简单动态字符串数据结构的实现 |
| 2  | `adlist.h`、`adlist.c` | 双向链表数据结构的实现 |
| 3  | `dict.h`、`dict.c` | 字典数据结构的实现 |
| 4  | `server.h` 中 `zskiplist` 和 `zskiplistNode` 结构、`t_zset.c` 中 `zsl` 开头的函数 | 跳跃表数据结构的实现 |
| 5  | `hyperloglog.c` 中 `hllhdr` 结构、所有以 `hll` 开头的函数 | HyperLogLog 数据结构的实现 |


References
-----------------

1. https://github.com/huangz1990/redis-3.0-annotated

2. https://blog.huangz.me/diary/2014/how-to-read-redis-source-code.html

