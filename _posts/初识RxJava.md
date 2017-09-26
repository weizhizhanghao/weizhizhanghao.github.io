---
title: 初识RxJava
date: 2017-09-20 11:01:30
tags: Android
---

### 方法解析
* onStart: 总是在subscribe所发生的线程被调用，而不能指定线程
* unsubscribe: 解除绑定，解除引用关系，避免内存泄漏的发生
* 