# ProtAgents 二级结构组成统计

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

计算、比较和检查螺旋、折叠等结构的占比。

## 输入、输出与 LLM 参与

- **输入**　蛋白三维结构文件。
- **输出**　各类二级结构所占百分比字典，含未归类项。
- **LLM 参与**　否，基于三维几何与 DSSP 规则。

## 结果解读

函数先依据 DSSP 给残基指派二级结构，再按类别汇总为百分比字典。未归类残基也保留在统计结果中。

## 在六篇研究中的用法

该组件记录于 **ProtAgents**，对应环节为实验 I–IV 结构分析。

## 原始来源与 GitHub

- **该研究中的定义**　[Ghafarollahi & Buehler (2024), ProtAgents: protein discovery via large language model multi-agent collaborations combining physics and machine learning](<https://doi.org/10.1039/D4DD00013G>)
- **DSSP 的原始出处**　[Kabsch & Sander (1983), Dictionary of protein secondary structure: pattern recognition of hydrogen-bonded and geometrical features](<https://doi.org/10.1002/bip.360221211>)
- **Biopython 的原始出处**　[Cock et al. (2009), Biopython: freely available Python tools for computational molecular biology and bioinformatics](<https://doi.org/10.1093/bioinformatics/btp163>)
- **GitHub 仓库**　[lamm-mit/ProtAgents](<https://github.com/lamm-mit/ProtAgents>)（研究项目仓库）。
- **归属说明**　ProtAgents 暴露计算接口，DSSP 定义二级结构赋值方法，BioPython 提供软件接口。

## 下载与访问

- [下载作者的工具函数源码](<https://raw.githubusercontent.com/lamm-mit/ProtAgents/7a73af3f746ca472a8524d1659547de7a54e65f5/agent_functions.py>)　这些函数与其他工具在同一个源文件中发布。
- [研究项目源码 ZIP](<https://api.github.com/repos/lamm-mit/ProtAgents/zipball/7a73af3f746ca472a8524d1659547de7a54e65f5>)　整个研究项目的源码快照。
- [研究论文 PDF](<https://arxiv.org/pdf/2402.04268>)　作者预印本 PDF。期刊正式版见 DOI。

## 关联组件

[Biopython](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/%E8%AE%A1%E7%AE%97%E7%8E%AF%E5%A2%83%E4%B8%8E%E8%BD%AF%E4%BB%B6%E5%BA%93/Biopython/Biopython.md) · [DSSP](../DSSP/DSSP.md) · [ProtAgents](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProtAgents/ProtAgents.md)
