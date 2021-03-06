[TOC]
# 面试知识点汇总
> 题目来自：https://mp.weixin.qq.com/s/joFBDntI9PmyVRiKPHwpRg
## c/c++相关
> c语言语法推荐书籍: 《c专家编程》《c与指针》  
 c++语言语言推荐书籍:《c++ primer》《effect c++》  
 c++语言stl底层原理：《STL源码剖析》
1. c++虚函数原理
1. 智能指针
1. c语言如何实现c++对象以及私有成员
1. c++多态实现
1. new和malloc的区别以及底层实现原理
1. STL中的vector怎么扩容
1. 虚函数指针的初始化过程
1. c++11原子变量介绍
1. c++11特性有哪些，说用过的
1. 怎么理解重载与重写
1. 怎么理解c++中的static关键字
1. vector和list 的区别
1. c++的内存分配
1. map与set的底层实现
1. 类静态变量的初始化
1. 析构函数可以是虚函数？为什么
1. 深拷贝与浅拷贝
1. 指针常量，常量指针的区别

## 计算机网络

> tcp/ip相关推荐书籍:《tcp/详解：1》  
熟悉使用wireshark捕包工具，加深印象可以使用python的一个库，scapy/dpkt.

1. 介绍下proactor和reactor
1. reactor的组成
1. TIME_WAIT危害
1. TIME_WAIT时长，为什么？
1. IP为什么要分片
1. 项目中说用到线程池，开多大，为什么运用线程池？
1. select和epoll区别
1. select什么情况返回0
1. epoll可读情况有哪些
1. 什么时候需要TCP四次挥手？
1. 如何设置非阻塞
1. 什么是零拷贝？
1. tcp与udp的区别以及应用场景
1. 如何设计一个可靠的udp
1. 粘包如何解决
1. 讲一下拥塞控制和流量控制
1. http和https区别
1. 是否了解中间人劫持原理
1. http协议格式，几种方法，功能是什么
1. chunked块了解？介绍下
1. 有chunked的时候contentlength是什么样子
1. 半连接在哪个阶段
1. 三次握手四次握手详细过程，越详细越好
1. libevent结构，内部实现
1. tcp的可靠性体现在哪里
1. ARP协议工作流程
1. epoll中的ET和LT模式
1. 介绍下滑动窗口
1. 指针与引用的区别
1. Accept发生在三次握手哪个阶段
1. Udp的接收缓冲区和发送缓冲区和tcp的区别
1. http长连接与短连接的区别
1. udp包长度
1. 一次url访问会经历哪些过程
1. 数据包乱序会处理？
1. seq为1000，发送了1000个数据，下一个seq是多少?
1. syn如果丢了，重传多少次

## 数据结构相关
> 数据结构书籍《大话数据结构》  
极客时间王大佬/谭大佬专栏


1. hash处理冲突的方法
1. 二分查找及其变种
1. 数组与链表的区别
1. redis数据结构用过哪些，了解跳表？
1. 红黑树比平衡二叉树有哪些优点
1. 二叉树，b+树，hash，二叉查找树区别
1. 说说红黑树的特性
1. 各种树，排序的时间复杂度
1. 数据库索引，事务，事务级别
1. 不考虑事务的隔离性会出现什么问题
1. 事务隔离级别
1. 索引的类型
1. AC自动机时间复杂度

## 数据库相关
> mysql书籍推荐:《mysql必知必会》，《高性能Mysql》，《mysql45讲》

1. 如何提高查询速度？
1. 加了索引就快了？
1. 数据库索引底层结构
1. mysql与memcache的区别
1. mysql常见三种存储引擎的
1. MySQL B+Tree索引和Hash索引的区别？
1. B+树索引和哈希索引的明显区别是：
1. 非关系型数据库和关系型数据库区别，优势比较？
1. mysql常见查询优化方案

## 操作系统

> 操作系统推荐书籍:《深入理解操作系统》，《Linux内核设计与实现》

1. 进程与线程的区别
1. 多进程与多线程区别，应用场景
1. volatile和原子变量的区别
1. proc文件系统
1. 自旋锁与普通锁的区别
1. 虚拟内存
1. 进程的内存分布
1. 栈内存为什么由系统自动分配和释放
1. 守护进程如何创建
1. 进程间的通信方式及其区别，应用场景
1. 死锁条件和解除
1. 进程调度方式
1. 对编译连接的理解
1. 共享内存实现原理
1. 僵尸进程是什么，如何处理
1. 自旋锁在单cpu与多cpu下的使用
1. 用户态与内核态

## Linux基础知识及应用编程
> Linux基础命令推荐书籍:《Linux就该这么学》  
Linux应用编程推荐书籍：《后台开发核心技术与应用实践》《Linux多线程服务端编程》《高性能Linux服务器编程》 《linux环境编程:从应用到内核》《unix高级环境编程》  
补充资料:gdb手册和makefile详解

1. 如何查看进程打开的文件
1. 介绍下nm与ldd命令
1. shell命令查内存，端口 ，io访问量，读写速率
1. awk grep具体应用
1. 硬链接与软连接，目录可不可以用硬链接
1. 常见命令netstat iptable tcpdump top
1. makefile介绍下(cmake介绍下)
1. gdb查看堆栈中所有遍历
1. gdb查看shared_ptr
1. 指向的内容
1. gdb如何调试多进程多线程
1. g++和gcc编译出来有什么区别
1. 死锁怎么调试
1. core文件中是什么，gdb调试core文件
1. 如何读取一个10G文件，cat一个10g文件会发生什么

## 大数问题
> 大数问题通常的套路是hash,分治，布隆，bitmap，如果推荐的话还是上面数据结构相关资料.当然如果能了解下比如hdfs文件系统，mapreduce，spark/flink流式计算最佳哈

1. 有200亿qq，但实际只有25亿用户，找到重复的qq
1. 25亿qq占用内存多大
1. 1-100万，计算找出所有的质数（计算密集型任务），用单线程与多线程怎么处理
1. 1个G的文件写程序，从A机器发送到B机器，怎么发？
1. 100G的文本，每行80k还是80字符，提示用多个机器，多进程，多线程，求出重复最多的行。一个机器内存8G，计算每个机器大概分多少？能读取100G的文本吗？找重复率前十的文本
三个有序的序列，查找公共的部分，第一次我说用哈希表，他说序列太大，空间复杂度要低点，我说了二分查找，他问三个序列查找的顺序和时间复杂度。（时间复杂度为N*logN *logN）
100WURL，如何存储
1. 10台服务器，100w用户，如何进行负载均衡，如何有个服务器挂掉了咋办
1. 10000个数据查找最小的100个？时间复杂度？
1. 场景题：QQ的服务器会保存登录用户的QQ号，只要有登录，文件里面就会有记录，现在需要统计哪些QQ号登录过，怎么做？（先说了分治用小文件，他说除了这个了，我说bit数组，他就问需要多大内存？）

## 手撕算法(递归非递归)
> 算法学习书籍推荐《剑指offer》，建议三遍哈。
leetcode分专栏练习几题，不在多，在于精。

1. 链表有无环判断
1. 实现一个单例模式
1. 给一个字符串判断单词数
1. 开方算法
1. 青蛙跳台阶
1. 常用排序(快排和归并要写吐)
1. 反转链表
1. 两个链表，寻找公共节点
1. 查找字符串中不重复的最长子串
1. LRU
1. 手写求树的深度的代码
1. 手写生产者消费者
1. 编程实现string类
1. 两个数组A,B，A有的B都有，求B-A；
1. 输入一个字符串，输出它的全排列
1. 统计完全二叉树多少个节点
1. memcpy实现

## 针对项目相关
> 最好是自己做过的项目，即时不是也需要弄明白其架构，为什么这么做，有什么优点，什么优化方案？

1. 介绍一个你做的比较的项目，几个人做的，担任什么角色
1. 项目的技术点在哪里
1. 项目不足在哪里
1. 你在项目中学到了什么
1. 让你优化项目中的一点，如何做
1. 项目什么架构
1. 测过系统性能吗，挂掉怎么办？

## 场景题
1. 给一个场景，设计一下定时对url进行爬虫，比如对新浪1个小时爬虫n次，然后某些博客可能1个星期爬虫1次。
1. 给一个场景，设计服务器实现爬虫的url去重，如何让多个服务器对一个url爬虫指定次数
1. 好多小文件，设计一个服务器来实现如何存储
1. 设计两地高效传文件

## 架构/分布式/中间件相关
> 推荐书籍：《redis设计与实现》《从0开始学架构》《docker入门到实践》《大型网站技术架构-核心原理与案例分析》

1. 常用负载均衡策略
1. 一致性hash原理
1. 缓存容灾中数据一致性问题
1. 了解cap理论吗
1. 介绍下高可用，高性能，可伸缩基本概念。。
1. 了解微服务？docker？k8s?
1. Nginx了解到什么程度，nginx配置更新实现，事件模型