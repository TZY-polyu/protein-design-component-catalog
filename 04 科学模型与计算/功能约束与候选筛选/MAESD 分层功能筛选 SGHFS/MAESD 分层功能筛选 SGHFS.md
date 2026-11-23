# MAESD 分层功能筛选 SGHFS

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

依次检查核心位点、局部微环境和整体构象。任一层失败即淘汰。

## 输入、输出与 LLM 参与

- **输入**　候选与参考结构、功能位点注释。
- **输出**　三层得分、逐层通过／失败、失败所处层级。
- **LLM 参与**　无需通用 LLM 裁判。子智能体按预设指标计算。

## 结果解读

三个层级依次检查核心位点、局部环境和整体构象。前一层未通过的候选在该轮停止，因此后层分数不能补偿前层失败。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时筛选框架。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　SGHFS 的命名及三层组合规则在本文提出。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
