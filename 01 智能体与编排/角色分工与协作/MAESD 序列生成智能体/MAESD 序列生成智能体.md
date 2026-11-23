# MAESD 序列生成智能体

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

为初始生成和后续结构条件生成调用不同科学模型。

## 输入、输出与 LLM 参与

- **输入**　结构域片段、GO 标签或前轮候选的预测骨架。
- **输出**　候选蛋白序列集合。
- **LLM 参与**　调用蛋白质语言模型和结构模型。未单列通用 LLM 后端。

## 结果解读

此角色调度 ProGen2 和 ProteinMPNN。论文分别说明两种生成任务的条件，未为角色另行指定通用 LLM 后端。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时角色。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　此处归属智能体角色。其调用的 ProGen2 和 ProteinMPNN 另列。

## 下载与访问

- [生成模块的适配器目录](<https://github.com/nnnnnnz/MAESD/tree/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/adapters>)　含 mock 与外部适配器。相应模型权重另行获取。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [ProGen2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProGen2/ProGen2.md) · [ProteinMPNN](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProteinMPNN/ProteinMPNN.md)
