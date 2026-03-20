# AI Agent / LLM 学习路径

这是一套按阶段推进的大模型工程学习路线，目标不是只会调 API，而是逐步具备下面这几类能力：

1. 看懂并解释 LLM、Agent、RAG、评测、部署优化的关键原理。
2. 能独立用主流工具链做出可运行的系统，而不是停留在概念层。
3. 能对一个系统做效果评估、性能优化、可观测性建设和工程化交付。
4. 能在每个章节结束后完成理论考试、代码考试和总结性项目，并接受打分。

## 使用方式

1. 按阶段顺序学习，不建议跳级。
2. 每个章节都先看 `学习资料/README.md`。
3. 学完后完成 `理论考试/README.md`。
4. 然后完成 `代码考试/README.md`。
5. 最后做 `实际项目/README.md`。
6. 你把答案、代码和项目结果整理给我后，我会按 [评分与晋级规则.md](/home/llm/AI_Agent_LLM_学习路径/评分与晋级规则.md) 评分，决定你是否进入下一章节或下一阶段。

## 阶段地图

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

## 推荐学习节奏

- 每周 1 个章节：适合有全职工作的人，周期大约 3 个月。
- 每周 2 个章节：适合已有后端或 AI 基础的人，周期大约 6 到 8 周。
- 每个章节分配建议：
  - 学习资料：20%
  - 理论考试：15%
  - 代码考试：30%
  - 实际项目：35%

## 默认技术栈

- Python 3.11+
- FastAPI
- Jupyter 或 Markdown 笔记
- LangChain / LangGraph
- Dify
- n8n
- FAISS / Elasticsearch / Milvus / Qdrant 中任选其一
- PostgreSQL / SQLite
- Docker
- vLLM
- OpenTelemetry / Langfuse / Phoenix / Helicone / Prometheus / Grafana 中任选组合

## 你完成后如何提交给我

参考 [提交流程.md](/home/llm/AI_Agent_LLM_学习路径/提交流程.md)。



## 持续学习与断点恢复

- 总进度记录在 [学习进度总览.md](/home/llm/AI_Agent_LLM_学习路径/学习进度总览.md)
- 当前恢复点在 [当前学习状态.md](/home/llm/AI_Agent_LLM_学习路径/当前学习状态.md)
- 使用方式见 [如何继续学习.md](/home/llm/AI_Agent_LLM_学习路径/如何继续学习.md)
