# MCP Python SDK

提供 Model Context Protocol 的 Python 客户端和服务端实现，支持发现工具、传递参数和接收响应。

## 输入与输出

- **输入**　客户端与服务端的能力声明、工具名、参数模式以及具体调用消息。
- **输出**　工具目录、资源内容、结构化响应或错误消息。底层程序决定科学结果的含义。

## 接入条件

- **LLM 参与**　协议自身不要求 LLM。调用者可以是智能体，也可以是普通程序。
- **运行条件**　兼容版本的 Python、客户端与实现相同协议版本的服务端。

MCP 只规定通信规则。判断某项调用是否需要通用 LLM、专用模型或数据库，要看对应服务实现。

## 原始来源与公开实现

Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）

[官方来源说明](https://www.anthropic.com/news/model-context-protocol)

- **GitHub 仓库**　[modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)
- **实现入口**　[查看源代码](https://github.com/modelcontextprotocol/python-sdk/blob/77001c96f9507be0f4d009b83210a384a5e08bda/src/mcp/client/session.py)

这是协议维护组织发布的 Python 实现。下面的首发公告介绍 MCP 协议。SDK 本身没有核实到独立论文。

## 下载

- [下载实现源码（ZIP）](https://github.com/modelcontextprotocol/python-sdk/archive/77001c96f9507be0f4d009b83210a384a5e08bda.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [Python 软件包](https://pypi.org/project/mcp/#files)　官方 SDK 的发布文件。
- [协议规范](https://modelcontextprotocol.io/specification)　核对服务能力、消息与协议版本。
