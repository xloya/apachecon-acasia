---
title: "小米 HDFS 数据治理实践与演进"
date: "2023-08-19T15:00:00" 
track: "datastorage"
presenters: "王成伟"
stype: "中文演讲"
---
简介：本次分享着重于介绍小米内部进行 HDFS 数据治理的背景，以及基于冷热数据分层存储思想进行的数据治理实践与演进，以及后续的数据治理规划。
大纲：
1.  背景
本节主要介绍小米内部 HDFS 的现状，以及进行 HDFS 数据治理的原因和目的。
1.  实践与演进
- 冷数据的定义与分析
本节主要介绍小米内部对于冷数据的定义，及分析与定位冷数据的方法。
- Tiering v1 方案介绍
本节主要介绍基于HDFS 异构存储功能，通过 fuse 挂载  S3 存储作为 Archive 盘存储冷数据的 Tiering v1 方案。包括  Tiering v1 方案的架构和原理，以及优点和存在的问题。
- Tiering v2方案介绍
本节主要介绍通过改造 HDFS 支持访问公有云 S3 的Tiering v2方案。包括Tiering v2方案的原理和整体架构；对 HDFS 进行的改造；如何转储冷数据到 S3 中；如何进行读取 S3 中的冷数据；如何对存储在S3 中的冷数据进行 GC；优势与存在的问题。
1. 总结与展望
本节主要介绍 HDFS 数据治理的实现的工作成果，以及为未来的规划，如支持直接 HDFS 直接写入 S3，支持对存在 S3 中的冷数据进行 append。
 ### Speakers: 
 <img src="https://img.bagevent.com/resource/20230601/1422115780.png" width="200" /><br>王成伟: 小米, 高级软件研发工程师, 小米高级软件开发工程师，HDFS  Contributor，多年的 HDFS 优化与维护经验。在小米主要负责 HDFS 相关的优化与维护工作。
 <br><br>