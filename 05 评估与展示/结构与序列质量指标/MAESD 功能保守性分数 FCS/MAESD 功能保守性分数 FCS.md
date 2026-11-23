# MAESD 功能保守性分数 FCS

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

横向比较设计与参照的计算一致性。该汇总指标和逐层淘汰规则用途不同。

## 输入、输出与 LLM 参与

- **输入**　SGHFS 三层对相应约束的满足程度。
- **输出**　归一化到0–100的功能保守性分数。
- **LLM 参与**　无需。对层级分数做算术汇总。

## 结果解读

FCS 将分层约束的满足程度汇总为 0–100 分，用于对不同设计作计算比较。该总分与流程内逐层筛选的通过状态各有含义。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为离线评估。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　指 MAESD 式10的具体指标。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
