---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - framework
repo: https://github.com/pydantic/pydantic-ai
priority: 选读
---

# pydantic-ai

Pydantic 团队的 agent 库。工具参数、依赖和输出用类型描述，校验发生在执行之前。

## 为什么读

对照 [[工具调用]]：schema 放在类型里和放在手写 JSON 里，运行时差在哪里。适合在你开始写自己的工具层时读，不必作为第一份源码。

## 本地代码

```powershell
git clone --depth 1 https://github.com/pydantic/pydantic-ai.git refs/pydantic-ai
```

## 阅读顺序

- [ ] 定义一个工具的最少代码
- [ ] 依赖注入进工具的方式
- [ ] 参数校验失败时，模型看到什么

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[工具调用]]
