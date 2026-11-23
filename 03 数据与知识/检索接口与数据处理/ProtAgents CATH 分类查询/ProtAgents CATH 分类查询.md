# ProtAgents CATH 分类查询

[数据与知识](../../README.md) / 检索接口与数据处理

## 用途

提取数据库中已注释的蛋白结构类别，用于实验 I 对照。

## 输入、输出与 LLM 参与

- **输入**　已知蛋白的 PDB 标识符。
- **输出**　相应的 CATH 结构分类编码。
- **LLM 参与**　否。

## 结果解读

函数返回已注释结构的 CATH 分类编码，编码含义由 CATH 数据库定义。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I 在线查询。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **CATH 的原始出处**　[Orengo et al. (1997), CATH—a hierarchic classification of protein domain structures](<https://doi.org/10.1016/S0969-2126(97)00260-8>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　查询接口由 ProtAgents 实现，分类体系与数据来自 CATH。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[CATH](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/CATH/CATH.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
