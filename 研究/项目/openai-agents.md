---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - framework
repo: https://github.com/openai/openai-agents-python
priority: 先读
---

# openai-agents

OpenAI Agents SDK 的 Python 实现。体积比一整套编排平台小，适合看官方如何把 handoff、guardrail 和 tracing 挂到一次运行上。

## 为什么读

在 [[smolagents]] 看懂循环之后，用它对照三件事：工具定义的官方写法、把对话交给另一个 agent 时传什么、以及运行轨迹从哪条 API 留下来。对应 [[多智能体]] 和 [[评估与可观测]]。

## 本地代码

```powershell
git clone --depth 1 https://github.com/openai/openai-agents-python.git refs/openai-agents-python
```

## 阅读顺序

- [ ] README 的最小 agent
- [ ] 一次 run 的主路径
- [ ] handoff 的数据结构
- [ ] guardrail 在循环的哪一侧执行
- [ ] tracing 记录了哪些字段

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[smolagents]]
