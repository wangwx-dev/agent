---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - framework
repo: https://github.com/huggingface/smolagents
priority: 先读
---

# smolagents

Hugging Face 的轻量 agent 库。核心循环短，适合作为读源码的第一站，对照 [[Agent循环]] 和 [[工具调用]]。

## 为什么读

看一个 agent 循环在真实代码里由哪些函数组成，以及 CodeAgent 如何把「写出代码并执行」当成工具，而不是另起一套运行时。

## 本地代码

```powershell
git clone --depth 1 https://github.com/huggingface/smolagents.git refs/smolagents
```

## 阅读顺序

- [ ] README 里的最短示例
- [ ] agent 主循环
- [ ] 工具如何注册、结果如何写回
- [ ] 步数上限和错误处理

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[学习地图]]
