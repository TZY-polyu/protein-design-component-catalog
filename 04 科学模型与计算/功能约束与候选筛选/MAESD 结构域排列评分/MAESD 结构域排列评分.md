# MAESD 结构域排列评分

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

比较候选结构域的顺序与天然蛋白中的典型顺序。

## 输入、输出与 LLM 参与

- **输入**　InterPro 同源序列中的结构域位置、候选排列。
- **输出**　每种结构域的位置先验和组合偏差分数。
- **LLM 参与**　无需。按位置统计计算。

## 结果解读

从同源蛋白估计各结构域出现的位置倾向，再衡量候选排列与该分布的偏离。评分反映参考数据中的常见顺序。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时约束构建。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　指正文给出的具体评分定义。InterPro 提供输入。

## 下载与访问

- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。

## 关联组件

[InterPro](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/InterPro/InterPro.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
