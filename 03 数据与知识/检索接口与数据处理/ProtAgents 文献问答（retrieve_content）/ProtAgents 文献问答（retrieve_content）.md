# ProtAgents 文献问答（retrieve_content）

[数据与知识](../../README.md) / 检索接口与数据处理

## 用途

把文献知识带入群聊。实验 I 出现过蛋白名与编号错误匹配。代理不能独立访问语料核实。

## 输入、输出与 LLM 参与

- **输入**　自然语言检索问题、文献知识库。
- **输出**　与问题相关的文字回答，如蛋白名称或 PDB 编号。
- **LLM 参与**　RAG 的生成环节需要语言模型。本文未指明其具体后端。

## 结果解读

该函数把文献片段组织成自然语言回答。作者报告了蛋白名称与 PDB 编号错配的实例，关键事实可回到原始文献核验。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I 在线检索。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **LlamaIndex 的原始出处**　[Liu (2022), LlamaIndex（软件项目，未核实独立方法论文）](<https://github.com/run-llama/llama_index>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　ProtAgents 定义检索接口，RAG 后端采用 LlamaIndex 官方软件。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[LlamaIndex](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E6%8E%A8%E7%90%86%E4%B8%8E%E6%A3%80%E7%B4%A2%E7%BC%96%E6%8E%92/LlamaIndex/LlamaIndex.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
