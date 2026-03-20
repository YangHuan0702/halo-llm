# 章节 03：LangChain 与 LangGraph 基础

## 学习目标

- 理解为什么需要框架层，而不是所有逻辑都手写。
- 掌握 Prompt、Model、Parser、Retriever、Tool、Memory、Graph 节点之间的关系。
- 能用 LangChain 或 LangGraph 组织一个最小流程。

## 理论重点

### 1. LangChain 适合什么

- 快速搭建链式流程
- 组织模型、检索、工具和解析器
- 便于实验和迭代

### 2. LangGraph 适合什么

- 状态机型 Agent
- 多分支决策
- 循环、重试、人类介入
- 长流程编排

### 3. 什么时候不要过度依赖框架

- 需求很简单时，手写代码更清晰
- 高性能或高可控场景可能需要自己封装
- 框架升级快，抽象可能变化

## 必学组件

- PromptTemplate
- OutputParser
- Runnable
- Tool
- State
- Node
- Edge
- Checkpoint

## 本章实操

1. 写一个 PromptTemplate。
2. 把模型调用和输出解析串起来。
3. 用 LangGraph 做一个两节点流程：
   - 问题分类
   - 根据分类走不同处理路径

## 完成标准

- 你能说清 LangChain 和 LangGraph 的定位差异。
- 你能实现一个含状态的最小图流程。
