# ProteinMCP 纳米抗体质量与结构展示

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

展示 pTM、ipTM、pAE 及界面指标，解释原生筛选结果。

## 输入、输出与 LLM 参与

- **输入**　BoltzGen 候选、置信度、界面描述量。
- **输出**　质量分布图、氢键与界面面积变化图、标注 CDR 的结构图。
- **LLM 参与**　指标及绘图本身无需通用 LLM。

## 结果解读

质量分布和标注图用于理解 BoltzGen 候选经过计算筛选后的特征。界面几何与结构置信度可分别查看。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为案例3计算评估与呈现。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **BoltzGen 的原始出处**　[Stark et al. (2025), BoltzGen: Toward Universal Binder Design](<https://doi.org/10.1101/2025.11.20.689494>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文负责汇总图，原生评分来自 BoltzGen。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [下载期刊补充材料（DOCX）](<https://pmc.ncbi.nlm.nih.gov/articles/instance/13140703/bin/PRO-35-e70547-s001.docx>)　期刊附件，含表 S1–S3 的服务和工作流技能目录。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[BoltzGen](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/BoltzGen/BoltzGen.md) · [ipTM](../ipTM/ipTM.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
