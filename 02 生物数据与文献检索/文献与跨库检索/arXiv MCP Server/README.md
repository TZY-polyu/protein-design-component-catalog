# arXiv MCP Server

按主题、作者、时间或分类检索 arXiv 预印本，发现适用的方法论文并检查指定版本。需要阅读时可获取相应文稿。

## 输入与输出

- **输入**　arXiv 检索式，或用于读取与下载的 arXiv 编号。可附分类、时间范围与分页参数。
- **输出**　题名、作者、摘要、arXiv 编号和链接。下载工具可将可访问论文保存到本地。

## 接入条件

- **LLM 参与**　检索和结果解析均无需 LLM。需要自然语言问答时，可由上层程序另行调用模型。
- **运行条件**　Python 3.11 或更高版本、项目依赖及联网访问 arXiv 的能力。保存全文需本地可写目录。代码许可为 Apache-2.0。

搜索返回的数据由 arXiv 提供。预印本可能更新，引用时可保存版本号。

## 原始来源与公开实现

Joseph Blazick 发布的 arXiv MCP Server 软件。未查到该连接器的独立原始论文。

- **GitHub 仓库**　[blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server)
- **实现入口**　[查看源代码](https://github.com/blazickjp/arxiv-mcp-server/blob/aeb82ecf0e3d6e44d6d1b0341aaef35be5d19df1/src/arxiv_mcp_server/tools/search.py)

客户端作者仓库，包含 arXiv 请求、Atom/XML 解析、分页和文稿下载实现。

## 下载

- [固定版本源码 ZIP](https://github.com/blazickjp/arxiv-mcp-server/archive/aeb82ecf0e3d6e44d6d1b0341aaef35be5d19df1.zip)　该快照包含组件实现及配套项目文件。
