# AI Agent / LLM Engineering Path

<p align="center">
  <strong>从会调用模型，到能交付 LLM / Agent 系统。</strong>
</p>

<p align="center">
  一个面向 <strong>LLM 工程</strong>、<strong>Agent 系统</strong>、<strong>RAG 架构</strong>、<strong>评测监控</strong> 与 <strong>部署优化</strong> 的系统化学习仓库。
</p>

<p align="center">
  <a href="./AI_Agent_LLM_学习路径/README.md"><img src="https://img.shields.io/badge/Path-12%20Chapters-111111?style=for-the-badge&logo=bookstack&logoColor=white" alt="12 Chapters"></a>
  <a href="./AI_Agent_LLM_学习路径/评分与晋级规则.md"><img src="https://img.shields.io/badge/Assessment-Theory%20%2B%20Code%20%2B%20Project-0A66C2?style=for-the-badge" alt="Assessment"></a>
  <a href="./AI_Agent_LLM_学习路径/学习进度总览.md"><img src="https://img.shields.io/badge/Progress-Trackable-0F766E?style=for-the-badge" alt="Progress Trackable"></a>
  <a href="./AI_Agent_LLM_学习路径/当前学习状态.md"><img src="https://img.shields.io/badge/Resume-Friendly-D97706?style=for-the-badge" alt="Resume Friendly"></a>
</p>

## Overview

这不是一个“API 调通就算学会”的仓库。

这是一个按阶段推进、按章节拆解、按考核验收的 **LLM / Agent 工程学习路径**。它的目标不是让你知道几个热门名词，而是让你真正具备下面这类能力：

- 看懂并解释 LLM、Prompt、Agent、RAG、评测、监控、部署优化的核心机制
- 独立完成一个 AI 应用从原型到工程化落地的关键环节
- 用考试、代码和项目结果证明自己不是“看过”，而是“做过”
- 在学习中断后也能依靠状态文件快速恢复上下文，持续推进

## Why This Repo

很多 AI 学习资料存在几个典型问题：

- 内容零散，知识点之间没有路径感
- 只讲概念，不要求你真正实现
- 做完 demo 就结束，没有评测、监控、优化和交付意识
- 学习一中断，就很难继续接上

这个仓库就是针对这些问题设计的：

- 用 **阶段化路线** 建立完整知识图谱
- 用 **理论考试 + 代码考试 + 实际项目** 约束学习质量
- 用 **评分与晋级机制** 阻止“假通关”
- 用 **学习进度总览 + 当前学习状态** 支持长期迭代式学习

## Highlights

- `Documentation-first`：以文档为主线，但每章都要求落到代码和项目
- `Engineering-first`：强调可运行、可验证、可交付，而不是概念背诵
- `Stage-based`：从基础到系统，从单点能力到完整工程闭环
- `Assessment-driven`：每章有明确评分结构和晋级门槛
- `Resume-friendly`：适合长期学习，不怕中断

## 使用方式
- `openclaw`: 如果使用的是claw类应用，直接将项目发给claw，让它根据当前项目环境进行学习
- `web AI`: 如果使用的是grok/gemini/gpt，可以直接通过AI_INSTRUCTIONS.md设置关键字的方式进行阶段式学习
- `CLi AI`(推荐方式): 初始化项目后，直接开始学习即可，简单高效。 
 
## Roadmap

### 阶段 0：准备与基础

- `章节01_LLM基础与工程环境`
- `章节02_Prompt_API_结构化输出`

### 阶段 1：应用框架与工作流编排

- `章节03_LangChain_LangGraph基础`
- `章节04_Dify与n8n自动化编排`

### 阶段 2：Agent 系统

- `章节05_单Agent_多工具_记忆`
- `章节06_多Agent_规划_人机协同`

### 阶段 3：RAG 系统

- `章节07_基础RAG_索引_召回`
- `章节08_混合检索_Rerank_QueryRewrite`
- `章节09_GraphRAG_知识图谱`

### 阶段 4：评测、监控与部署优化

- `章节10_自动化评测流水线`
- `章节11_LLM全链路监控与可观测性`
- `章节12_本地模型部署_量化_蒸馏_LoRA_vLLM`

完整学习地图见 [AI_Agent_LLM_学习路径/README.md](/home/llm/AI_Agent_LLM_学习路径/README.md)。

## Learning Loop

每个章节固定由 4 个部分组成：

- `学习资料`：建立概念、工具链和方法论
- `理论考试`：验证理解是否扎实
- `代码考试`：验证是否能独立实现核心能力
- `实际项目`：把章节知识做成一个可验证闭环

统一目录模板如下：

```text
阶段N_主题/
└── 章节NN_主题/
    ├── 学习资料/README.md
    ├── 理论考试/README.md
    ├── 代码考试/README.md
    └── 实际项目/README.md
```

## Repo Structure

```text
AI_Agent_LLM_学习路径/
├── README.md
├── 学习进度总览.md
├── 当前学习状态.md
├── 提交流程.md
├── 评分与晋级规则.md
├── 阶段0_准备与基础/
├── 阶段1_应用框架与工作流编排/
├── 阶段2_Agent系统/
├── 阶段3_RAG系统/
└── 阶段4_评测_监控与部署优化/
```

核心文档入口：

- [总览地图](/home/llm/AI_Agent_LLM_学习路径/README.md)
- [提交流程](/home/llm/AI_Agent_LLM_学习路径/提交流程.md)
- [评分与晋级规则](/home/llm/AI_Agent_LLM_学习路径/评分与晋级规则.md)
- [学习进度总览](/home/llm/AI_Agent_LLM_学习路径/学习进度总览.md)
- [当前学习状态](/home/llm/AI_Agent_LLM_学习路径/当前学习状态.md)

## How To Start

1. 打开 [AI_Agent_LLM_学习路径/README.md](/home/llm/AI_Agent_LLM_学习路径/README.md)，先看全局路线。
2. 根据 [当前学习状态.md](/home/llm/AI_Agent_LLM_学习路径/当前学习状态.md) 找到当前章节。
3. 先完成该章节的 `学习资料`。
4. 再完成 `理论考试`、`代码考试`、`实际项目`。
5. 按 [提交流程.md](/home/llm/AI_Agent_LLM_学习路径/提交流程.md) 提交结果。
6. 根据 [评分与晋级规则.md](/home/llm/AI_Agent_LLM_学习路径/评分与晋级规则.md) 接受评分和晋级判断。
7. 更新 [学习进度总览.md](/home/llm/AI_Agent_LLM_学习路径/学习进度总览.md) 与 [当前学习状态.md](/home/llm/AI_Agent_LLM_学习路径/当前学习状态.md)。

## Assessment

每章满分 `100` 分：

- 理论考试：`25` 分
- 代码考试：`35` 分
- 实际项目：`40` 分

默认晋级标准：

- `85+`：可直接进入下一章节
- `75-84`：可晋级，但必须补薄弱项
- `60-74`：不建议晋级，需要补交修正版
- `<60`：必须重做

同时存在单项硬门槛，所以不是总分高就一定过。详细规则见 [评分与晋级规则.md](/home/llm/AI_Agent_LLM_学习路径/评分与晋级规则.md)。

## Default Stack

这条学习路径默认围绕以下技术栈展开：

- Python 3.11+
- FastAPI
- LangChain / LangGraph
- Dify
- n8n
- FAISS / Elasticsearch / Milvus / Qdrant
- PostgreSQL / SQLite
- Docker
- vLLM
- OpenTelemetry / Langfuse / Phoenix / Helicone / Prometheus / Grafana

这意味着它不仅关心“能不能做出来”，也关心“怎么做稳、怎么观测、怎么优化”。

## Who Is This For

- 想系统补齐 LLM / Agent 工程能力的后端或全栈开发者
- 做过一些 AI demo，但缺少工程化方法的人
- 想从 Prompt 使用者升级为 AI 应用构建者的人
- 想搭建一套长期可追踪、可考核、可复盘学习系统的人

如果你只想快速抄一个 demo，这个仓库会显得偏重。
如果你想建立真正可迁移的 AI 工程能力，这个仓库就是为你设计的。

## Current Status

根据当前记录：

- 当前阶段：`阶段0_准备与基础`
- 当前章节：`章节01_LLM基础与工程环境`
- 整体进度：`0 / 12`
- 最近更新时间：`2026-03-20`

当前恢复入口：

- [AI_Agent_LLM_学习路径/README.md](/home/llm/AI_Agent_LLM_学习路径/README.md)
- [当前学习状态.md](/home/llm/AI_Agent_LLM_学习路径/当前学习状态.md)

## Quick Checks

仓库目前没有统一构建入口，但可以用这些命令做基础检查：

```bash
rg --files AI_Agent_LLM_学习路径
find AI_Agent_LLM_学习路径 -name README.md | sort
git diff -- AGENTS.md
```

如果你在某个章节加入了代码实现，建议把该章节自己的运行方式、依赖说明、测试命令和预期输出写进对应 README。

## One-Line Pitch

一个把 **学习路径**、**工程训练**、**项目实战**、**评分晋级** 和 **长期进度管理** 打包在一起的 LLM / Agent 工程仓库。

不是让你“知道”，而是让你“做成”。
