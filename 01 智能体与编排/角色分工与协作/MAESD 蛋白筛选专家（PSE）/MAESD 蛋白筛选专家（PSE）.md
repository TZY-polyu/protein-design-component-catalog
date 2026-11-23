# MAESD 蛋白筛选专家（PSE）

[智能体与编排](../../README.md) / 角色分工与协作

## 用途

汇合科学工具的结果，调度三层功能检查。

## 输入、输出与 LLM 参与

- **输入**　候选序列、预测结构、参考结构与功能要求。
- **输出**　结构、能量、功能检查结果及反馈。
- **LLM 参与**　智能体编排。具体数值由工具和预设逻辑计算，未单列其 LLM 后端。

## 结果解读

PSE 汇集计算检查结果并给出反馈。分层筛选分数属于计算估计，论文未通过湿实验逐一验证候选功能。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时角色。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　该角色和三层筛选的组合由 MAESD 定义。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
