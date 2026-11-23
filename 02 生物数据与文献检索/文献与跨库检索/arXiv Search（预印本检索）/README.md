# arXiv Search（预印本检索）

为论文元数据建索引，按关键词、标题、作者和学科条件检索预印本。

## 输入与输出

- **输入**　用于建立索引的论文元数据，以及查询词、字段或筛选条件。
- **输出**　检索结果列表、论文元数据和记录链接。

## 接入条件

- **LLM 参与**　数据库检索与文件下载无需 LLM。
- **运行条件**　自建服务需要 Elasticsearch 和可供索引的论文元数据。

本软件是 arXiv 的官方检索服务。文稿投稿、存储和文件分发由其他服务负责。

## 原始来源与公开实现

arXiv Search 未见独立方法论文。软件来源是 arXiv 官方项目和发布记录。

[官方来源说明](https://github.com/arXiv/arxiv-search#readme)

- **GitHub 仓库**　[arXiv/arxiv-search](https://github.com/arXiv/arxiv-search)
- **实现入口**　[查看源代码](https://github.com/arXiv/arxiv-search)

arXiv 官方检索服务实现。

## 下载

- [官方源码 ZIP](https://github.com/arXiv/arxiv-search/archive/refs/heads/develop.zip)　获取 develop 分支快照。
