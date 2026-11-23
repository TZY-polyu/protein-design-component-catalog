# ProteinMCP 结合蛋白质量与界面展示

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

并列展示 pLDDT、ipTM、ipAE、界面分数、SASA 等计算证据。

## 输入、输出与 LLM 参与

- **输入**　预测复合物、结构置信度和物理评分。
- **输出**　质量散点图、界面面积与能量图、结构视图。
- **LLM 参与**　指标及绘图本身无需通用 LLM。

## 结果解读

在同一组候选中并列查看置信度、几何与能量，为结果比较提供互补证据。该展示使用计算结果。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为案例2计算评估与呈现。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **Rosetta 的原始出处**　[Simons et al. (1997), Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions.](<https://doi.org/10.1006/jmbi.1997.0959>)
- **Rosetta 的原始出处**　[Simons et al. (1999), Ab initio protein structure prediction of CASP III targets using ROSETTA.](<https://pubmed.ncbi.nlm.nih.gov/10526365/>)
- **AlphaFold2 的原始出处**　[Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.](<https://doi.org/10.1038/s41586-021-03819-2>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文生成汇总图，底层结构与能量指标分别由专用工具提供。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [下载期刊补充材料（DOCX）](<https://pmc.ncbi.nlm.nih.gov/articles/instance/13140703/bin/PRO-35-e70547-s001.docx>)　期刊附件，含表 S1–S3 的服务和工作流技能目录。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[AlphaFold2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [ipTM](../ipTM/ipTM.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [Rosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md)
