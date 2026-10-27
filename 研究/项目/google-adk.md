---
type: oss-project
status: 待研究
language: Python
tags:
  - oss
  - framework
repo: https://github.com/google/adk-python
priority: 选读
---

# google-adk

Google 的 Agent Development Kit（Python）。关注他们如何划分 runner、session 和 tool，而不是先学某一家模型的 API。

## 为什么读

大厂 SDK 通常把「一次运行」和「会话」拆开。用来检验自己的应用是不是把这两件事堆在同一个对象里。

## 本地代码

```powershell
git clone --depth 1 https://github.com/google/adk-python.git refs/adk-python
```

## 阅读顺序

- [ ] 一次运行从哪个对象开始
- [ ] session 里保存什么
- [ ] 工具回调或插件挂在哪一层

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[记忆]]
