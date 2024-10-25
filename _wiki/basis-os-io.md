---
layout: wiki
title: I/O 模型
cate1: Basis
cate2:
description: I/O 模型
keywords: Basis
---

## 概念理解

### 同步与异步

多个任务和事件发生时，一个事件的发生或执行是否会导致整个流程的暂时等待。

### 阻塞与非阻塞

当请求一个操作时，如果条件不满足，是会一直等待还是返回一个标志信息。

### 同步 I/O 与异步 I/O

数据拷贝阶段是由用户线程完成还是内核完成（必须要有操作系统的底层支持）。

### 阻塞 I/O 与非阻塞 I/O

在数据未就绪的情况下，是返回一个标志位还是一直等待。

## I/O 模型

### 阻塞 I/O 模型

### 非阻塞 I/O 模型

### 多路复用 I/O 模型

Java NIO 属于这一种，使用 select() 去查询每个通道是否有到达事件，没有事件则阻塞。

### 信号驱动 I/O 模型

### 异步 I/O 模型

## 参考

* [Java NIO：浅析I/O模型](http://www.cnblogs.com/dolphin0520/p/3916526.html)