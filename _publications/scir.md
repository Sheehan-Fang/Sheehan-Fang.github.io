---
title: "SCIR：用于增强 schema 信息抽取的迭代自校正优化框架"
collection: publications
permalink: /publication/scir
venue: AAAI
conference_year: 2026
publication_status: accepted
venue_note: Oral
author_role: 第一作者
keywords: [信息抽取, 指令微调, 大语言模型, 自然语言处理]
excerpt: '通过双路径自校正与 MBSC 偏好对齐数据集，提升信息抽取的准确性、鲁棒性和泛化能力。'
---

**关键词：**信息抽取；指令微调；大语言模型；自然语言处理。

针对基于 LLM 的信息抽取系统训练成本高、偏好难对齐及泛化能力不足等问题，提出即插即用的 SCIR 框架与 MBSC 偏好对齐数据集。

SCIR 通过双路径自校正模块结合规则约束与反馈驱动优化，在降低训练资源消耗的同时提升系统稳定性与推理效率。MBSC 通过间接蒸馏 GPT-4 的推理与偏好能力，提供高质量偏好监督信号，缓解传统监督微调中的输出不稳定问题。实验表明，该方案提升了复杂信息抽取场景下的准确性、鲁棒性与泛化能力。
