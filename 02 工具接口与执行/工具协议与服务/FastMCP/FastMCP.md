# FastMCP

[工具接口与执行](../../README.md) / 工具协议与服务

## 用途

把可调用函数、资源和提示模板暴露成 MCP 服务，让工具宿主发现接口、传入参数并读取结果。

## 输入、输出与 LLM 参与

- **输入**　工具定义、类型或参数约束，以及来自 MCP 客户端的调用请求。
- **输出**　可发现的工具清单、工具返回值或错误信息。
- **LLM 参与**　服务框架自身无需 LLM。语言模型可以在上层决定调用哪个工具。

## 结果解读

应记录导入路径和软件版本。独立的 fastmcp 包及 MCP Python SDK 内的同名类可能具有不同接口。

## 在六篇研究中的用法

- **ProteinMCP**（平台建置／扩展）　把现有科学代码包装为 MCP 服务。

使用此来源的研究组件包括 [ProteinMCP 服务生成器（MCPCreator）](../ProteinMCP%20%E6%9C%8D%E5%8A%A1%E7%94%9F%E6%88%90%E5%99%A8%EF%BC%88MCPCreator%EF%BC%89/ProteinMCP%20%E6%9C%8D%E5%8A%A1%E7%94%9F%E6%88%90%E5%99%A8%EF%BC%88MCPCreator%EF%BC%89.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[Jeremiah Lowin / FastMCP 项目。未查到独立的方法论文](<https://github.com/PrefectHQ/fastmcp>)
- **GitHub 仓库**　[PrefectHQ/fastmcp](<https://github.com/PrefectHQ/fastmcp>)
- **归属说明**　论文未报告实现版本。ProteinMCP 官方架构文档示范从独立的 fastmcp 包导入。部分实现采用过官方 SDK 的内置类，两者不能据名称等同。

## 下载与访问

- [FastMCP 软件包](<https://pypi.org/project/fastmcp/#files>)　独立 fastmcp 项目的软件发行文件。
- [仓库源码 ZIP · PrefectHQ/fastmcp](<https://github.com/PrefectHQ/fastmcp/archive/64f43a2f9aae44e8a94f5a4faf94e3d46324a0bf.zip>)　该仓库的固定快照。

## 关联组件

[MCP](../MCP/MCP.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
