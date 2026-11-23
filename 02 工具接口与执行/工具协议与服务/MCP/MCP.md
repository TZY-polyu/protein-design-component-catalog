# MCP

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

规定智能体宿主怎样发现工具、传递参数、调用服务并接收结果，让不同软件使用一致的通信方式。

## 输入、输出与 LLM 参与

- **输入**　客户端与服务端的能力声明、工具名、参数模式以及具体调用消息。
- **输出**　工具目录、资源内容、结构化响应或错误消息。底层程序决定科学结果的含义。
- **LLM 参与**　协议自身不要求 LLM。调用者可以是智能体，也可以是普通程序。

## 结果解读

MCP 只规定通信规则。判断某项调用是否需要通用 LLM、专用模型或数据库，要看对应服务实现。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProteinMCP 工具调用器](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E8%B0%83%E7%94%A8%E5%99%A8/ProteinMCP%20%E5%B7%A5%E5%85%B7%E8%B0%83%E7%94%A8%E5%99%A8.md)、[AutoBinder MCP 通信层](../AutoBinder%20MCP%20%E9%80%9A%E4%BF%A1%E5%B1%82/AutoBinder%20MCP%20%E9%80%9A%E4%BF%A1%E5%B1%82.md)、[AutoBinder 工具服务层](../AutoBinder%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E5%B1%82/AutoBinder%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1%E5%B1%82.md)、[ProteinMCP 服务层](../ProteinMCP%20%E6%9C%8D%E5%8A%A1%E5%B1%82/ProteinMCP%20%E6%9C%8D%E5%8A%A1%E5%B1%82.md)、[Latent Labs 平台 MCP 服务](../Latent%20Labs%20%E5%B9%B3%E5%8F%B0%20MCP%20%E6%9C%8D%E5%8A%A1/Latent%20Labs%20%E5%B9%B3%E5%8F%B0%20MCP%20%E6%9C%8D%E5%8A%A1.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[Anthropic (2024), Introducing the Model Context Protocol（官方首发公告）](<https://www.anthropic.com/news/model-context-protocol>)
- **GitHub 仓库**　[modelcontextprotocol/modelcontextprotocol](<https://github.com/modelcontextprotocol/modelcontextprotocol>)
- **归属说明**　协议由 Anthropic 发布。

## 下载与访问

- [官方协议规范](<https://modelcontextprotocol.io/specification>)　可在线查阅版本化规范。规范与运行服务的 SDK 是两类资源。
- [仓库源码 ZIP · modelcontextprotocol/modelcontextprotocol](<https://github.com/modelcontextprotocol/modelcontextprotocol/archive/862397cec702e8f828713071da501cf56158e8fc.zip>)　该仓库的固定快照。
