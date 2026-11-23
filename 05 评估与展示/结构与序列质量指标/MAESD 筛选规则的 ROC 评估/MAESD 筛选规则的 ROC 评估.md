# MAESD 筛选规则的 ROC 评估

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

以参考数据分析筛选规则的区分能力。

## 输入、输出与 LLM 参与

- **输入**　天然结构、突变体活性参照与 FSM 分数。
- **输出**　ROC 曲线及分层筛选判别点的灵敏度、特异度。
- **LLM 参与**　无需。

## 结果解读

将连续 FSM 分数与已知参照标签比较，观察不同判定点下灵敏度和特异度的变化。这是研究对筛选阈值的离线校准。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为离线指标校准。

## 原始来源与 GitHub

- **方法来源**　通用方法或统计量，未确认唯一首发论文。
- **该研究的记载**　[MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　ROC 属于通用判别分析方法。以它校准 FSM 阈值是 MAESD 的实验。

## 下载与访问

- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
