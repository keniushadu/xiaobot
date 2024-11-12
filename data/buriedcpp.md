# C++埋点SDK项目实战_小报童_Awesome_XiaoBOT

## C++埋点SDK项目实战介绍
> 【终身订阅】C++客户端埋点相关的SDK实战项目。适合入门和进阶C++的同学。  
  


|名称|作者|读者数量|内容数量|更新时间|
|---|---|---|---|---|
|[C++埋点SDK项目实战](https://xiaobot.net/p/buriedcpp?refer=9c3f1c95-a052-465a-9902-f6d75080262a)|程序喵|305人|19篇|2024-06-14|

## 最近更新
### 【C++埋点SDK实战】加餐-如何在简历中体现这个项目

之前在埋点项目答疑群中，收到读者反馈，希望我能出一期文章，介绍如何在简历中描述这个项目。

所以，本文来了。

对于任何项目的介绍，我建议大家都尽量使用STAR......

### 【C++埋点SDK实战】15-结束语

大家好，我是程序喵。

在之前的章节中，我已经详细介绍了整个C++埋点项目。本节主要是为了给这个项目画上一个句号。

通过这个项目，我介绍了许多与......

### 【C++埋点SDK实战】14-整体功能组装

大家好，我是程序喵。

在前面的章节中，我向大家详细介绍了项目中各个子模块的实现，包括公共信息获取模块、多线程模块、上报模块、数据库模块、加解密模块以及三方库等模块。

### 【C++埋点SDK实战】加餐-spdlog源码分析

源码地址：github.com/gabime/spdlog

架构

如图，其实也不只是spdlog，几乎所有的Log模块都是这样的架构：

### 【C++埋点SDK实战】13-公共信息获取

大家好，我是程序喵。

上一章节中，我介绍了项目中上报模块的实现，本节我们来点轻松的，介绍下如何获取公共信息。

为什么要获取公共信息？

<......

### 【C++埋点SDK实战】12-上报模块实现

大家好，我是程序喵。

在前面几期中，我已经介绍过如何发起http通信，如何实现加解密功能，如何进行多线程开发，这一期，我会把这些能力整合到一起，完成整个上报模块。

### 【C++埋点SDK实战】11-多线程开发

大家好，我是程序喵。

本节我主要向大家介绍埋点项目中的多线程模块。

估计正常做C++多线程开发，大多数朋友都是这样写代码：

std::t......

### 【C++埋点SDK实战】10-加解密实现

大家好，我是程序喵。

前面我介绍过数据库的作用，会在上报前先把数据按一定格式存储到数据库中，用于持久化，防止信息丢失，而且也提到过，存储内容一定要是加密过的数据，防止数......

### 【C++埋点SDK实战】9-如何发起http请求

大家好，我是程序喵。

前面我们设计了上报的协议，并且确定使用http协议做埋点的网络上报。

HTTP请求是基于TCP协议的，它涉及以下几个主要......

### 【C++埋点SDK实战】8-数据库设计与使用

大家好，我是程序喵。

上一节介绍了上报协议的设计，这一节我会主要介绍埋点项目中，数据库的结构设计与使用。

提到数据库，大家肯定会想到MySQL、Postgr......


<a href="https://github.com/Reno9527/awesome-xiaobot" style="color: white; text-decoration: none;">awesome-xiaobot</a>

返回 [首页](../README.md)