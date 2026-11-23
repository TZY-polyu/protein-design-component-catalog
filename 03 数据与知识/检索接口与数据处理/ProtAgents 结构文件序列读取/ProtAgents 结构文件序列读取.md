# ProtAgents 结构文件序列读取

[数据与知识](../../README.md) / 检索接口与数据处理

## 用途

从数据库条目或已生成结构中读取序列，供其他步骤使用。

## 输入、输出与 LLM 参与

- **输入**　PDB 标识符或结构文件名。
- **输出**　氨基酸序列。
- **LLM 参与**　否。

## 结果解读

该函数通过结构对象读取链中的序列，适用于下载的结构和本地生成文件。它列于工具清单，正文未分别展示执行记录。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为已列入可调用工具。正文未单列调用示例。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **Chroma 的原始出处**　[Ingraham et al. (2023), Illuminating protein space with a programmable generative model](<https://doi.org/10.1038/s41586-023-06728-8>)
- **Protein Data Bank 的原始出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　ProtAgents 用 Chroma 的 Protein 对象读取序列。公开结构来自 PDB，也支持本地结构。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[Chroma](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/Chroma/Chroma.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [Protein Data Bank](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Protein%20Data%20Bank/Protein%20Data%20Bank.md)
