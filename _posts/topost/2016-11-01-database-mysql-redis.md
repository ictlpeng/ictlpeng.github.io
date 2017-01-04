---
layout: post
title: 使用databus实现mysql与redis的数据同步
---


[Databus](https://github.com/linkedin/databus)是LinkedIn开源的分布式数据增量抓取系统(change data capture system)。从个人理解来看，Databus主要用于数据的抓取与传播，用于同步、分发、迁移等场景。



1）设置mysql（使用binlog replication的方式读取数据）

参考：http://dev.mysql.com/doc/refman/5.5/en/replication-howto.html

