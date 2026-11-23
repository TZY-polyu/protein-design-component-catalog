# MAESD 测试集与同源过滤

[数据与知识](../../README.md) / 文献与研究数据

## 用途

过滤不完整注释和高相似序列，限制训练与测试数据的同源重叠。

## 输入、输出与 LLM 参与

- **输入**　人工审阅条目、家族种子比对、PDB 结构、生成模型训练集参照。
- **输出**　作者报告的1,000条蛋白测试集、另选400个高分辨率结构。
- **LLM 参与**　无需通用 LLM。

## 结果解读

作者用序列与结构数据构建彼此有区别的评测集合。同源过滤旨在降低训练与测试材料过于相似造成的偏差。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为离线数据准备。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **UniProt 的原始出处**　[Apweiler 等 (2004). UniProt: the Universal Protein knowledgebase.](<https://doi.org/10.1093/nar/gkh131>)
- **Pfam 的原始出处**　[Sonnhammer et al. (1997), Pfam: a comprehensive database of protein domain families based on seed alignments](<https://pubmed.ncbi.nlm.nih.gov/9223186/>)
- **Protein Data Bank 的原始出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　样本编选和过滤方案出自 MAESD。底层记录出自所列数据库。

## 下载与访问

仓库列有 Pfam 种子样本。实验数据组成及统计见 ACS 免费补充材料，尚未确认所有原始数据和权重都随仓库分发。期刊正文按出版商访问权限获取。

- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [Pfam](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Pfam/Pfam.md) · [Protein Data Bank](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Protein%20Data%20Bank/Protein%20Data%20Bank.md) · [Swiss-Prot](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Swiss-Prot/Swiss-Prot.md) · [UniProt](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/UniProt/UniProt.md)
