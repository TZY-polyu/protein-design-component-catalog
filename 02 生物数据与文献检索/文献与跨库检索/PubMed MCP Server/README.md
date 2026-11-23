# PubMed MCP Server

使用 NCBI E-utilities 搜索 PubMed，按 PMID 取回题录与摘要，也能尝试获取带有开放全文的文稿。

## 输入与输出

- **输入**　检索词，或题名、作者、期刊等检索条件。读取单条记录时传入 PMID。
- **输出**　匹配的 PMID、题名、作者、期刊、摘要等可用字段。对能定位公开全文的条目可额外获取 PDF。

## 接入条件

- **LLM 参与**　检索和结果解析均无需 LLM。需要自然语言问答时，可由上层程序另行调用模型。
- **运行条件**　Python 环境、项目列出的依赖及访问 NCBI 的网络。代码采用 MIT 许可，文献全文有各自的使用条款。

有 PubMed 记录并不保证有摘要或开放 PDF，文献使用条件取决于出版方与全文来源。

## 原始来源与公开实现

JackKuo666 发布的 PubMed MCP Server 软件。未查到该连接器的独立原始论文。

- **GitHub 仓库**　[JackKuo666/PubMed-MCP-Server](https://github.com/JackKuo666/PubMed-MCP-Server)
- **实现入口**　[查看源代码](https://github.com/JackKuo666/PubMed-MCP-Server/blob/2a254f418f431e7ee5c161e38c8144890d52c20b/pubmed_web_search.py)

连接器作者仓库，含 MCP 服务、查询构造与 PubMed XML 解析。

## 下载

- [固定版本源码 ZIP](https://github.com/JackKuo666/PubMed-MCP-Server/archive/2a254f418f431e7ee5c161e38c8144890d52c20b.zip)　该快照包含组件实现及配套项目文件。
