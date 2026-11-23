# MAESD 模块消融与迭代评测

[评估与展示](../../README.md) / 智能体评测与基线

## 用途

分别检验 IRA、PSE、DE、EL 的贡献，估算迭代收益与执行开销。

## 输入、输出与 LLM 参与

- **输入**　完整系统、去掉指定模块或改变迭代次数的实验输出及运行记录。
- **输出**　结构／功能指标变化和 CPU、GPU、内存、耗时对照。
- **LLM 参与**　统计本身无需。被测系统可调用 LLM。

## 结果解读

移除模块可观察其对最终结果的影响。改变迭代次数并记录耗时与资源占用，则可同时比较边际收益和计算成本。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为仅离线评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　仅指本研究的实验设计。消融、敏感性分析及 CPU/GPU 计量本身属于通用方法。

## 下载与访问

- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
