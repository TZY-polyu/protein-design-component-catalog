# MAESD 意图识别标签评测

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

检验 IRA 将自然语言转化为生物学约束的质量。

## 输入、输出与 LLM 参与

- **输入**　根据文本预测的 GO／结构域标签、UniProt 专家注释。
- **输出**　精确率、召回率、F1（表列）。另讨论覆盖率及误发现率。
- **LLM 参与**　指标计算无需。被考察的语义模型使用 LLM。

## 结果解读

把预测标签与已有专家注释对齐后计算精确率、召回率与 F1，用以判断自然语言需求是否被转成正确的生物学约束。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为仅离线评估。

## 原始来源与 GitHub

- **方法来源**　通用方法或统计量，未确认唯一首发论文。
- **该研究的记载**　[MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　精确率、召回率和 F1 属于通用评测指标。本文比较任务所用真值由 UniProt 注释提供。

## 下载与访问

- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[Gene Ontology](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/Gene%20Ontology/Gene%20Ontology.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [UniProt](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/UniProt/UniProt.md)
