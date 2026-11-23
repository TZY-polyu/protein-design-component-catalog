# LlamaIndex

把论文等文档切分为可检索内容，组织索引、检索器和回答生成器，供智能体按问题取回证据。

## 输入与输出

- **输入**　建库时读取文档与元数据，查询时接收自然语言问题或检索条件。
- **输出**　检索命中的文本片段和出处。启用回答合成时，还返回基于检索结果的文字回答。

## 接入条件

- **LLM 参与**　建立索引和检索可独立执行。回答合成是否调用通用 LLM 取决于应用配置。
- **运行条件**　Python 和对应检索后端。若配置嵌入模型或回答生成，还需本地模型或所选提供方的访问权限。

检索器返回的证据受所建索引、分块方式及检索配置限制。

## 原始来源与公开实现

Liu (2022), LlamaIndex（软件项目，未核实独立方法论文）

[官方来源说明](https://github.com/run-llama/llama_index)

- **GitHub 仓库**　[run-llama/llama_index](https://github.com/run-llama/llama_index)
- **实现入口**　[查看源代码](https://github.com/run-llama/llama_index/blob/99d7433f6f71888951379ccca9294e272442c832/llama-index-core/llama_index/core/query_engine/retriever_query_engine.py)

LlamaIndex 维护的仓库包含独立的核心索引与查询模块。

## 下载

- [下载实现源码（ZIP）](https://github.com/run-llama/llama_index/archive/99d7433f6f71888951379ccca9294e272442c832.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [Python 发布包](https://pypi.org/project/llama-index/#files)　可下载当前发行包，历史版本见 Release history。
