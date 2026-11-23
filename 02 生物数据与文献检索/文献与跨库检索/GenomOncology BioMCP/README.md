# GenomOncology BioMCP

将多个生物医学数据源的文献、临床和生物标志物等记录统一暴露为可查询的接口。

## 输入与输出

- **输入**　关键词、疾病或变异等实体标识符、筛选条件及可用的数据源访问权限。
- **输出**　带标识符或来源线索的检索结果、摘要和结构化记录。

## 接入条件

- **LLM 参与**　作为数据工具服务无需通用 LLM。上层智能体可以选择查询并解释结果。
- **运行条件**　本地发行程序或 Rust 工具链。查询在线数据源需要网络，部分来源使用各自的访问凭据。

项目提供命令行和 MCP 两种入口。能返回的字段取决于所查数据源及其发布版本。

## 原始来源与公开实现

GenomOncology (2025), BioMCP 发布。作者按软件引用，未查到独立的方法论文

[官方来源说明](https://genomoncology.com/press-releases/genomoncology-announces-biomcp-open-source-model-context-protocol-mcp-for-biomedical-ai-assistants-and-agents/)

- **GitHub 仓库**　[genomoncology/biomcp](https://github.com/genomoncology/biomcp)
- **实现入口**　[查看源代码](https://github.com/genomoncology/biomcp/blob/561d3fe06d9dff5485f13a82a4108371f6fdfe88/src/lib.rs)

GenomOncology 维护的 BioMCP 实现，当前仓库包含本地命令与工具服务代码。

## 下载

- [下载实现源码（ZIP）](https://github.com/genomoncology/biomcp/archive/561d3fe06d9dff5485f13a82a4108371f6fdfe88.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [BioMCP 官方发行版](https://github.com/genomoncology/biomcp/releases)　GenomOncology 维护的版本、软件包及发布说明。
