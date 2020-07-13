# redis 源代码剖析
###  redis 版本：2020-06最新版，也就是5.0.5
#### 从2020-06-29开始，会逐渐将解读后的代码（带中文注释）上传。如果您发现我的解读存在问题，请联系我哟！
----
#### 数据结构篇
时间|发布内容|博客链接
:--:|:--:|:--:
2020-06-29|发布redis的内存管理模块源代码解读，主要在zmalloc.h、zmalloc.c文件中|待定
2020-06-29|发布redis的动态字符串（sds）源代码解读，主要在sds.h、sds.c文件中|待定
2020-06-30|发布redis的链表（list）源代码解读，主要在alist.h、alist.c文件中|待定
2020-06-30|发布redis的字典（dict）源代码解读，主要在dict.h、dict.c文件中|待定
2020-07-01|发布redis的压缩表（ziplist）源代码解读，主要在ziplist.h、ziplist.c文件中|待定
2020-07-02|发布redis的快表（quicklist）源代码解读，主要在quicklist.h、quicklist.c文件中|待定
2020-07-03|发布redis的整数集合（intset）源代码解读，主要在intset.h、intset.c文件中|待定
2020-07-04|发布redis的跳跃表（skiplist）源代码解读，主要在server.h、t_zset.c文件中|待定
2020-07-06|hyperloglog(正在进行中)|待定
2020-07-08|geo（正在进行中）|待定
2020-07-10|bloomfilter布隆过滤器（正在进行中）|待定
2020-07-13|发布redis的对象（redisoject）源代码解读，主要在server.h和object.c文件中|待定

----
#### REDIS操作命令篇
时间|发布内容|博客链接
:--:|:--:|:--:
