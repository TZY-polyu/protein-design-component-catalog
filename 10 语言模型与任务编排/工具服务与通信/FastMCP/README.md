# FastMCP

把可调用函数、资源和提示模板暴露成 MCP 服务，让工具宿主发现接口、传入参数并读取结果。

## 输入与输出

- **输入**　工具定义、类型或参数约束，以及来自 MCP 客户端的调用请求。
- **输出**　可发现的工具清单、工具返回值或错误信息。

## 接入条件

- **LLM 参与**　服务框架自身无需 LLM。语言模型可以在上层决定调用哪个工具。
- **运行条件**　Python 和 fastmcp 发布包。服务暴露的每个外部工具按其自身要求配置。

应记录导入路径和软件版本。独立的 fastmcp 包及 MCP Python SDK 内的同名类可能具有不同接口。

## 原始来源与公开实现

Jeremiah Lowin / FastMCP 项目。未查到独立的方法论文

[官方来源说明](https://github.com/PrefectHQ/fastmcp)

- **GitHub 仓库**　[PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp)
- **实现入口**　[查看源代码](https://github.com/PrefectHQ/fastmcp/blob/64f43a2f9aae44e8a94f5a4faf94e3d46324a0bf/fastmcp_slim/fastmcp/server/server.py)

这里收录独立的 FastMCP 项目。MCP Python SDK 曾集成同名接口，导入路径及版本可以帮助区分实现。

## 下载

- [下载实现源码（ZIP）](https://github.com/PrefectHQ/fastmcp/archive/64f43a2f9aae44e8a94f5a4faf94e3d46324a0bf.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [FastMCP 软件包](https://pypi.org/project/fastmcp/#files)　独立 fastmcp 项目的软件发行文件。
