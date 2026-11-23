# LlamaIndex

[智能体与编排](../../README.md) / 推理与检索编排

## 用途

把论文等文档切分为可检索内容，组织索引、检索器和回答生成器，供智能体按问题取回证据。

## 输入、输出与 LLM 参与

- **输入**　建库时读取文档与元数据，查询时接收自然语言问题或检索条件。
- **输出**　检索命中的文本片段和出处。启用回答合成时，还返回基于检索结果的文字回答。
- **LLM 参与**　建立索引和检索可独立执行。回答合成是否调用通用 LLM 取决于应用配置。

## 结果解读

ProtAgents 使用它访问文献知识库。检索所覆盖的文献范围会限定回答能够援引的证据。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 文献问答（retrieve_content）](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%A3%80%E7%B4%A2%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86/ProtAgents%20%E6%96%87%E7%8C%AE%E9%97%AE%E7%AD%94%EF%BC%88retrieve_content%EF%BC%89/ProtAgents%20%E6%96%87%E7%8C%AE%E9%97%AE%E7%AD%94%EF%BC%88retrieve_content%EF%BC%89.md)。

## 原始来源与 GitHub

- **原始文献或官方出处**　[Liu (2022), LlamaIndex（软件项目，未核实独立方法论文）](<https://github.com/run-llama/llama_index>)
- **GitHub 仓库**　[run-llama/llama_index](<https://github.com/run-llama/llama_index>)
- **归属说明**　作者提供软件引文。

## 下载与访问

- [Python 发布包](<https://pypi.org/project/llama-index/#files>)　可下载当前发行包，历史版本见 Release history。
- [仓库源码 ZIP · run-llama/llama_index](<https://github.com/run-llama/llama_index/archive/99d7433f6f71888951379ccca9294e272442c832.zip>)　该仓库的固定快照。
