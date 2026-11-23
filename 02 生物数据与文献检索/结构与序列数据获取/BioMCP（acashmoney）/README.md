# BioMCP（acashmoney）

通过 MCP 查询 RCSB PDB 中的结构、已记录的位点和配体信息，也可按疾病或研究主题检索相关结构。

## 输入与输出

- **输入**　一个 PDB 编号，或用于数据库检索的疾病名称和关键词。
- **输出**　结构条目的文本摘要、可取得的位点与残基注释，或附 PDB 编号的检索结果。位点字段的覆盖取决于数据库条目。

## 接入条件

- **LLM 参与**　查询由服务向数据 API 发起，可以用兼容的 MCP 客户端直接调用。用对话式助手发起查询时可搭配通用 LLM。
- **运行条件**　需要 Node.js 20 或更新版本、项目的 npm 依赖和到 RCSB 数据接口的网络连接。

维护者为 acashmoney。其结构检索服务和 GenomOncology 的同名 BioMCP 是两个独立发布的软件。

## 原始来源与公开实现

acashmoney，BioMCP: Enabling agent-based biomedical R&D，作者软件仓库。项目未列出独立方法论文。

- **GitHub 仓库**　[acashmoney/bio-mcp](https://github.com/acashmoney/bio-mcp)
- **实现入口**　[查看源代码](https://github.com/acashmoney/bio-mcp/tree/eb153e774fb63efedede77ecca43ccd5021aed5a/src/tools)

仓库公开查询处理函数和 MCP 服务端，可检查请求构造以及实际读取的返回字段。

## 下载

- [下载固定版本源码（ZIP）](https://github.com/acashmoney/bio-mcp/archive/eb153e774fb63efedede77ecca43ccd5021aed5a.zip)　解压后可按上面的实现入口定位组件。
