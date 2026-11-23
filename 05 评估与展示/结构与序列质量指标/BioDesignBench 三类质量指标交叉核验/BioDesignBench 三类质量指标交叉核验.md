# BioDesignBench 三类质量指标交叉核验

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

检查质量评分对不同结构、序列及物理代理指标的一致程度。

## 输入、输出与 LLM 参与

- **输入**　各条件候选的 Boltz-2 结构置信度、ESM-2 困惑度和逐残基 Rosetta 能量。
- **输出**　三种指标的分布及两两相关性。
- **LLM 参与**　仅蛋白语言模型（ESM-2 分量）

## 结果解读

作者比较结构置信度、序列困惑度与物理能量的分布和相关性。三项量测对候选的刻画角度不同。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为运行后／独立核对。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **Boltz-2 的原始出处**　[Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction](<https://doi.org/10.1101/2025.06.14.659707>)
- **ESM-2 的原始出处**　[Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model](<https://doi.org/10.1126/science.ade2574>)
- **Rosetta 的原始出处**　[Simons et al. (1997), Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions.](<https://doi.org/10.1006/jmbi.1997.0959>)
- **Rosetta 的原始出处**　[Simons et al. (1999), Ab initio protein structure prediction of CASP III targets using ROSETTA.](<https://pubmed.ncbi.nlm.nih.gov/10526365/>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　此交叉核验属本文评估。所用三种底层工具各有来源。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[BioDesignBench](../../%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Boltz-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/Boltz-2/Boltz-2.md) · [ESM-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E8%9B%8B%E7%99%BD%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E5%BA%8F%E5%88%97%E8%A1%A8%E5%BE%81/ESM-2/ESM-2.md) · [Rosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md)
