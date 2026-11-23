# BioDesignBench 结构质量独立复算

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

正文和补充D称用 Boltz-2。补充A.3/A.5 描述按任务使用 AF2/AF2-Multimer、ColabFold 与 PyRosetta。两种口径并存，均无 LLM 质量打分。

## 输入、输出与 LLM 参与

- **输入**　最终候选及独立后端计算的指标。
- **输出**　Quality 分项（0–35分）
- **LLM 参与**　否（专用模型＋算法）

## 结果解读

报告的质量分上限为 35。正文与补充材料的不同章节描述了不同的复算后端，均将该分项交由计算指标评定。

## 在六篇研究中的用法

该组件记录于 **BioDesignBench**，对应环节为提交后／质量评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Kim & Romero (2026), Benchmarking and behavioral characterization of LLM agents for protein design](<https://www.biorxiv.org/content/10.64898/2026.05.06.723381v1>)
- **Boltz-2 的原始出处**　[Passaro et al. (2025), Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction](<https://doi.org/10.1101/2025.06.14.659707>)
- **AlphaFold2 的原始出处**　[Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.](<https://doi.org/10.1038/s41586-021-03819-2>)
- **AlphaFold-Multimer 的原始出处**　[Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer](<https://doi.org/10.1101/2021.10.04.463034>)
- **ColabFold 的原始出处**　[Mirdita et al. (2022), ColabFold: making protein folding accessible to all](<https://doi.org/10.1038/s41592-022-01488-1>)
- **PyRosetta 的原始出处**　[Chaudhury et al. (2010), PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta](<https://doi.org/10.1093/bioinformatics/btq007>)
- **GitHub 仓库**　[RomeroLab/BioDesignBench](<https://github.com/RomeroLab/BioDesignBench>)（研究项目仓库）。
- **归属说明**　35分属于本基准。作者材料对具体复评后端的描述不一致。

## 下载与访问

- [质量评分模块目录](<https://github.com/RomeroLab/BioDesignBench/tree/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce/biodesignbench/eval/tier2>)　公开的结构设计评分层。
- [研究项目源码 ZIP](<https://api.github.com/repos/RomeroLab/BioDesignBench/zipball/cdf5c51a59222afa126e59dbfe8cbd0e96ad0bce>)　整个研究项目的源码快照。
- [v1 补充材料（PDF）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)　表 S1 逐项列出接口。

## 关联组件

[AlphaFold-Multimer](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold-Multimer/AlphaFold-Multimer.md) · [AlphaFold2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [BioDesignBench](../../%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [Boltz-2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/Boltz-2/Boltz-2.md) · [ColabFold](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/ColabFold/ColabFold.md) · [PyRosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/PyRosetta/PyRosetta.md)
