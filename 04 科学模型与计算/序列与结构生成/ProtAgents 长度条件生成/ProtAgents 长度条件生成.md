# ProtAgents 长度条件生成

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

生成规定长度的蛋白，用于比较生成结构与序列重折叠结构。

## 输入、输出与 LLM 参与

- **输入**　期望序列长度、结果名称。
- **输出**　候选氨基酸序列、三维结构及 PDB 文件名。
- **LLM 参与**　无需通用 LLM。采用专业生成模型 Chroma。

## 结果解读

该函数把长度和结果名称交给 Chroma，将生成的序列与三维结构关联到输出文件。生成结构还可与同一序列的独立折叠结果比较。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 II 生成。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **Chroma 的原始出处**　[Ingraham et al. (2023), Illuminating protein space with a programmable generative model](<https://doi.org/10.1038/s41586-023-06728-8>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　长度条件工具由 ProtAgents 封装，生成模型与相应能力源自 Chroma。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[Chroma](../Chroma/Chroma.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
