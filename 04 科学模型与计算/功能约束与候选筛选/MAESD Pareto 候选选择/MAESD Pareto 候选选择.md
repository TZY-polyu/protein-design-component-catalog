# MAESD Pareto 候选选择

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

先保留非支配候选，再按用户指定目标的优先级做字典序排序。无偏好时选距归一化理想点最近的候选。

## 输入、输出与 LLM 参与

- **输入**　通过筛选的候选及其结构、能量、功能排名。用户优先级。
- **输出**　非支配候选集合。按用户偏好或默认规则选出的候选。
- **LLM 参与**　Pareto 判断及偏好决胜均按显式规则执行。用户或上层代理可传入偏好。

## 结果解读

非支配关系给出多个折中候选，随后才依据用户偏好或理想点距离选出结果。同一前沿中的候选可以各自在不同指标占优。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时决策算法。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　偏好排序规则见 MAESD 补充材料 Part E。正文引用 Deb 等 (2002) 的 NSGA-II 作背景，未声称直接运行 NSGA-II。

## 下载与访问

- [下载 decision.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/decision.py>)　公开框架中用于选择候选的模块。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。
- [ACS 免费补充材料（PDF）](<https://ndownloader.figshare.com/files/62778364>)　作者在 ACS Figshare 发布，含数据集统计、分析说明和排序规则。 此次自动检查返回 HTTP 403，文件下载状态未确认。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
