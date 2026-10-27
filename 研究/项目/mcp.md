---
type: oss-project
status: 待研究
language: 规范
tags:
  - oss
  - protocol
repo: https://github.com/modelcontextprotocol/modelcontextprotocol
priority: 先读
---

# mcp

Model Context Protocol 的规范与讨论。概念笔记在 [[MCP协议]]，这篇只跟踪规格和你真正连上的 server。

## 为什么读

确认 host、client、server 的职责，以及工具描述在协议里的字段。读规范时以生命周期和 tools 两节为先，资源、提示模板和采样可以后补。

## 本地代码

```powershell
git clone --depth 1 https://github.com/modelcontextprotocol/modelcontextprotocol.git refs/modelcontextprotocol
```

需要可运行的例子时，再单独克隆官方的服务器或 SDK 仓库，目录名写在下面，不要和规范仓库混在一个目录里。

## 阅读顺序

- [ ] 架构概述：谁发起连接
- [ ] 工具列表和工具调用的消息
- [ ] 错误如何返回给 host
- [ ] 一个你关心的 server 实现，对照上面的消息

## 设计判断

### 值得借鉴

### 不打算借鉴

### 入口文件

-

## 关联

- [[研究索引]]
- [[MCP协议]]
- [[工具调用]]
