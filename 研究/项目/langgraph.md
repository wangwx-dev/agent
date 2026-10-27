---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - framework
repo: https://github.com/langchain-ai/langgraph
priority: 先读
---

# langgraph

用图描述 agent 的步骤和状态。重点不是「图」这个词，而是状态可以检查点化：暂停、恢复、人工插入、从失败的节点重试。

## 为什么读

阶段 2 要分清工作记忆和检查点。这个仓库是检查点做得最明确的实现之一，对照 [[记忆]] 和 [[规划]]。单代理循环已经能工作时再读，避免一开始被图的抽象挡住。

## 本地代码

```powershell
git clone --depth 1 https://github.com/langchain-ai/langgraph.git refs/langgraph
```

## 阅读顺序

- [ ] 状态对象里有哪些字段
- [ ] 一个节点执行完，状态如何合并
- [ ] 检查点保存和恢复的调用点
- [ ] 人工中断时，恢复后从哪条边继续

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[记忆]]
