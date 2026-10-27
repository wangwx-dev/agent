---
type: oss-project
status: 待研究
language: TypeScript
tags:
  - oss
  - observability
repo: https://github.com/langfuse/langfuse
priority: 选读
---

# langfuse

LLM 应用的 trace、提示词和评估数据平台。阶段 5 再读，用来对照 [[评估与可观测]] 里自己列的字段是否够用。

## 为什么读

看一次生成或一次 agent 运行在数据模型里是什么：trace、observation、score 如何关联。小应用可以先写本地 JSON，字段对齐之后再决定要不要接它。

## 本地代码

```powershell
git clone --depth 1 https://github.com/langfuse/langfuse.git refs/langfuse
```

## 阅读顺序

- [ ] trace 和 span 的区分
- [ ] 工具调用被记成哪种 observation
- [ ] 评分如何挂到一次运行上

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[评估与可观测]]
