---
title: "BanyanDB:一个高扩展性的分布式追踪数据库"
date: "2023-08-20T14:30:00" 
track: "cloudnative"
presenters: "高洪涛"
stype: "中文演讲"
---
追踪数据是一种用于分析微服务系统性能和故障的重要数据源，它记录了系统中每个请求的调用链路和相关指标。随着微服务系统的规模和复杂度的增长，追踪数据的量级也呈指数级增长，给追踪数据的存储和查询带来了巨大的挑战。传统的关系型数据库或者时序数据库往往难以满足追踪数据的高效存储和灵活查询的需求。

BanyanDB是一个专为追踪数据而设计的分布式数据库，它具有高扩展性、高性能、高可用性和高灵活性的特点。BanyanDB采用了基于时间序列的分片策略，将追踪数据按照时间范围划分为多个分片，每个分片可以独立地进行存储、复制和负载均衡。BanyanDB还支持多维索引，可以根据不同的维度对追踪数据进行快速过滤和聚合。

在本次演讲中，我们将介绍BanyanDB的设计思想、架构和实现细节，以及它在实际场景中的应用和效果。我们也将展示BanyanDB与其他数据库的对比和优势，以及它未来的发展方向和计划。
 ### Speakers: 
 <img src="https://img.bagevent.com/resource/20230522/0032233353684942.jpeg" width="200" /><br>高洪涛: Tetrate, 创始工程师, 美国servicemesh服务商tetrate创始工程师。原华为软件开发云技术专家，对云原生产品有丰富的设计，研发与实施经验。对分布式数据库，容器调度，微服务，ServicMesh等技术有深入的了解。
目前为Apache ShardingSphere和Apache SkyWalking核心贡献者，参与该开源项目在软件开发云的商业化进程。前当当网系统架构师，开源达人，曾参与Elastic-Job等知名开源项目。对开源项目的管理，推广和社区运营有丰富的经验。
积极参与技术分享，曾在多个技术大会中做过分享，包括DTCC，ArchSummit, Top100，Oracle嘉年华等。在多个媒体发表过文章，如InfoQ，OSChina等

 <br><br>