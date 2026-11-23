# MAESD 结构新颖性与序列多样性评测

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

分别评价预测置信度、结构差异、序列重复程度和组成偏差。

## 输入、输出与 LLM 参与

- **输入**　候选结构、参考结构和序列、同一提示或跨任务的候选集合。
- **输出**　pLDDT、TM-score、RMSD、折叠新颖性比例、序列一致性及氨基酸频率。
- **LLM 参与**　指标汇总无需通用 LLM。pLDDT 来自结构预测。

## 结果解读

该组合分别比较局部结构置信度、整体几何和序列组成。每项数字需结合所用参照与候选集合才可解释。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为离线评估。部分指标也用于筛选。

## 原始来源与 GitHub

- **AlphaFold2 的原始出处**　[Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.](<https://doi.org/10.1038/s41586-021-03819-2>)
- **TM-score 的原始出处**　[Zhang & Skolnick (2004). Scoring function for automated assessment of protein structure template quality.](<https://doi.org/10.1002/prot.20264>)
- **本研究中的用法**　[MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　pLDDT 由 AlphaFold2 输出。TM-score 有独立原始论文。RMSD、序列一致性与频率是通用统计量。

## 下载与访问

- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[AlphaFold2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [TM-score](../TM-score/TM-score.md)
