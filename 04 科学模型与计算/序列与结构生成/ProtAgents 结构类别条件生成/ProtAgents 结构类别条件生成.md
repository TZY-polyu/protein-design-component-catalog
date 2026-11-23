# ProtAgents 结构类别条件生成

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

按结构类别生成候选。论文观察到部分预期富 β 的产物实际富 α。

## 输入、输出与 LLM 参与

- **输入**　CATH 结构类别、长度、结果名称。
- **输出**　候选氨基酸序列、三维结构及 PDB 文件名。
- **LLM 参与**　无需通用 LLM。采用专业生成模型 Chroma。

## 结果解读

CATH 类别规定期望折叠类型。论文案例中曾出现实际二级结构成分偏离类别要求的结果，事后结构检查因此有独立作用。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 III–IV 生成。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **Chroma 的原始出处**　[Ingraham et al. (2023), Illuminating protein space with a programmable generative model](<https://doi.org/10.1038/s41586-023-06728-8>)
- **CATH 的原始出处**　[Orengo et al. (1997), CATH—a hierarchic classification of protein domain structures](<https://doi.org/10.1016/S0969-2126(97)00260-8>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　接口由 ProtAgents 封装，条件生成由 Chroma 执行，类别定义来自 CATH。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[CATH](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/CATH/CATH.md) · [Chroma](../Chroma/Chroma.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
