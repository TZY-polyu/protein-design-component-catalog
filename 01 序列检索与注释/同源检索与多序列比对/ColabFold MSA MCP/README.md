# ColabFold MSA MCP

向 ColabFold 的公共序列检索服务提交蛋白质序列，把返回的同源序列比对保存为本地文件，便于交给需要多序列比对的工具。

## 输入与输出

- **输入**　单条蛋白质氨基酸序列，可指定输出文件名或任务名。实现将查询发送到 ColabFold 的在线服务。
- **输出**　一个 A3M 格式的多序列比对文件及其本地路径。后端服务返回压缩包时，客户端提取其中第一个 A3M 文件。

## 接入条件

- **LLM 参与**　不需要。MCP 客户端可以直接调用已注册的工具，搜索和比对由 ColabFold 服务处理。
- **运行条件**　Python、FastMCP、requests，以及访问 ColabFold 公共 MSA 服务的网络连接。该客户端不含本地序列数据库。

此软件承担提交、轮询和文件解析。搜索的覆盖范围及可用时段取决于公共服务端的数据库和运行状态。

## 原始来源与公开实现

未检索到这款客户端的独立原始论文。实现随 MacromNex/msa_mcp 软件仓库发布。

- **GitHub 仓库**　[MacromNex/msa_mcp](https://github.com/MacromNex/msa_mcp)
- **实现入口**　[查看源代码](https://github.com/MacromNex/msa_mcp/blob/93c1d902bd4e19aa0cec32997345209a9636d4d9/src/tools/msa_generation.py)

这是 MacromNex 发布的第三方客户端。ColabFold 团队另行维护后端。

## 下载

- [固定版本源码 ZIP](https://github.com/MacromNex/msa_mcp/archive/93c1d902bd4e19aa0cec32997345209a9636d4d9.zip)　含客户端、工具注册和文件下载解析实现。
