# ProtAgents 结构下载函数

[数据与知识](../../README.md) / 检索接口与数据处理

## 用途

获取已知蛋白结构，使后续结构计算能使用坐标。

## 输入、输出与 LLM 参与

- **输入**　公开结构的 PDB 标识符。
- **输出**　本地结构坐标文件及其文件名。
- **LLM 参与**　否。

## 结果解读

函数按 PDB 标识获取已有坐标并交还本地文件名。结构的实验或建模来源见相应 PDB 条目。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I 在线取数。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **Protein Data Bank 的原始出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　函数由 ProtAgents 封装，结构数据来自 PDB 档案。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [Protein Data Bank](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Protein%20Data%20Bank/Protein%20Data%20Bank.md)
