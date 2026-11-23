# MAESD 演化循环（EL）

[智能体与编排](../../README.md) / 规划与反馈机制

## 用途

协调生成、筛选与决策，保留各目标间有取舍的候选。

## 输入、输出与 LLM 参与

- **输入**　结构域约束、天然模板或片段、结构参照及每轮反馈。
- **输出**　多轮迭代后的非支配候选集合。
- **LLM 参与**　混合。接收 IRA 的 LLM 输出，循环控制由算法与智能体完成。

## 结果解读

循环将生成、筛选和选择串在一起，终点可能是一组在不同计算指标上各有优势的候选。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为系统主模块。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　此模块体现了 MAESD 对生成、筛选和决策的具体编排。

## 下载与访问

- [下载 orchestrator.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/orchestrator.py>)　该项目的源码文件。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
