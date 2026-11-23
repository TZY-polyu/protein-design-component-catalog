# ProtAgents 简正模态分析

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

用各向异性网络模型比较不同结构的天然振动特征。文章称为频率。

## 输入、输出与 LLM 参与

- **输入**　蛋白结构及所需的模态数。
- **输出**　前若干振动模态对应的数值列表。
- **LLM 参与**　否，弹性网络物理计算。

## 结果解读

简正模态结果描述结构在弹性网络近似下的集体运动。比较不同结果时需要相同的模型假设和模态编号。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I–III 物理计算。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **ANM (Atilgan et al., 2001) 的原始出处**　[Atilgan et al. (2001), Anisotropy of fluctuation dynamics of proteins with an elastic network model](<https://doi.org/10.1016/S0006-3495(01)76033-X>)
- **ProDy 的原始出处**　[Bakan, Meireles & Bahar (2011), ProDy: Protein Dynamics Inferred from Theory and Experiments](<https://doi.org/10.1093/bioinformatics/btr168>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　ProtAgents 暴露的函数使用 ANM 方法与 ProDy 软件实现。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[ProDy](../ProDy/ProDy.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md) · [各向异性弹性网络模型（ANM）](../%E5%90%84%E5%90%91%E5%BC%82%E6%80%A7%E5%BC%B9%E6%80%A7%E7%BD%91%E7%BB%9C%E6%A8%A1%E5%9E%8B%EF%BC%88ANM%EF%BC%89/%E5%90%84%E5%90%91%E5%BC%82%E6%80%A7%E5%BC%B9%E6%80%A7%E7%BD%91%E7%BB%9C%E6%A8%A1%E5%9E%8B%EF%BC%88ANM%EF%BC%89.md)
