---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - domain-agent
repo: https://github.com/All-Hands-AI/OpenHands
priority: 选读
---

# openhands

面向软件工程任务的 agent：编辑文件、运行命令、观察测试结果。用来看垂直 agent 如何把危险动作关在沙箱里，以及观察如何喂回循环。

## 为什么读

如果你要做的应用会改代码或跑命令，这里的动作边界比通用聊天框架更接近问题本身。仓库大，先看动作接口和一次任务的事件流。

## 本地代码

```powershell
git clone --depth 1 https://github.com/All-Hands-AI/OpenHands.git refs/OpenHands
```

## 阅读顺序

- [ ] agent 能执行的动作有哪些
- [ ] 命令输出如何截断后回到模型
- [ ] 沙箱或运行环境的边界画在哪里

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[Agent循环]]
