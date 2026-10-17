---
title: "GEAR-UIE：面向统一信息抽取的图嵌入增强检索方法"
collection: publications
permalink: /publication/gear-uie
venue: ACL
conference_year: 2026
publication_status: accepted
venue_note: Main
author_role: 第一作者
keywords: [信息抽取, Graphormer, RAG, 大语言模型, 自然语言处理]
excerpt: '联合建模语义与混合句法图，结合 LLM 偏好重排序，在 11 个中英文统一信息抽取基准上取得性能提升。'
---

**关键词：**信息抽取；Graphormer；RAG；大语言模型；自然语言处理。

针对基于 RAG 的统一信息抽取系统在复杂长文本中仅依赖语义检索、易出现句法错位与结构关联缺失的问题，提出 GEAR-UIE 框架。

该框架融合依存句法分析与成分句法分析构建混合句法图，基于 Graphormer 编码文本结构，实现语义与句法结构联合建模；结合 LLM 偏好重排序，对候选检索结果进行细粒度相关性排序，增强实体关系、事件结构及跨句依赖理解能力。在 11 个中英文统一信息抽取基准数据集上取得显著性能提升。
