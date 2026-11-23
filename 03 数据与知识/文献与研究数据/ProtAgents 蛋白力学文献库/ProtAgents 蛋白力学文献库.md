# ProtAgents 蛋白力学文献库

[数据与知识](../../README.md) / 文献与研究数据

## 用途

为实验 I 的蛋白名称、结构与力学知识检索提供外部来源。

## 输入、输出与 LLM 参与

- **输入**　两篇蛋白质力学论文的全文。
- **输出**　供 LlamaIndex 查询的文献内容。
- **LLM 参与**　静态数据源不要求。

## 结果解读

实验 I 的知识范围来自两篇既定文献。检索结果只能反映这部分语料，具体来源可追溯到各篇原始文献。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为离线资料／在线被查询。

## 原始来源与 GitHub

- **Sikora et al. (2009) 的原始出处**　[Sikora, Sułkowska & Cieplak (2009), Mechanical Strength of 17,134 Model Proteins and Cysteine Slipknots](<https://doi.org/10.1371/journal.pcbi.1000547>)
- **Sułkowska & Cieplak (2007) 的原始出处**　[Sułkowska & Cieplak (2007), Mechanical stretching of proteins—a theoretical survey of the Protein Data Bank](<https://doi.org/10.1088/0953-8984/19/28/283201>)
- **本研究中的用法**　[ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　两篇原始蛋白力学研究的全文被选作检索语料。

## 下载与访问

- [文献索引文件目录](<https://github.com/lamm-mit/ProtAgents/tree/7a73af3f746ca472a8524d1659547de7a54e65f5/protein_force_index>)　包含文档存储和向量索引文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [Sikora et al. (2009) 原始发布入口](<https://doi.org/10.1371/journal.pcbi.1000547>)
- [Sułkowska & Cieplak (2007) 原始发布入口](<https://doi.org/10.1088/0953-8984/19/28/283201>)
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [Sikora 等的蛋白力学研究（2009）](../Sikora%20%E7%AD%89%E7%9A%84%E8%9B%8B%E7%99%BD%E5%8A%9B%E5%AD%A6%E7%A0%94%E7%A9%B6%EF%BC%882009%EF%BC%89/Sikora%20%E7%AD%89%E7%9A%84%E8%9B%8B%E7%99%BD%E5%8A%9B%E5%AD%A6%E7%A0%94%E7%A9%B6%EF%BC%882009%EF%BC%89.md) · [Sułkowska 与 Cieplak 的蛋白拉伸研究（2007）](../Su%C5%82kowska%20%E4%B8%8E%20Cieplak%20%E7%9A%84%E8%9B%8B%E7%99%BD%E6%8B%89%E4%BC%B8%E7%A0%94%E7%A9%B6%EF%BC%882007%EF%BC%89/Su%C5%82kowska%20%E4%B8%8E%20Cieplak%20%E7%9A%84%E8%9B%8B%E7%99%BD%E6%8B%89%E4%BC%B8%E7%A0%94%E7%A9%B6%EF%BC%882007%EF%BC%89.md)
