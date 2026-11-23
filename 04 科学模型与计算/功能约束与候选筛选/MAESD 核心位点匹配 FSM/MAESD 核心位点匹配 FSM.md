# MAESD 核心位点匹配 FSM

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

量化核心位点的空间相似性。

## 输入、输出与 LLM 参与

- **输入**　经叠合的候选与参考结构、核心位点的原子坐标。
- **输出**　功能位点匹配分数 FSM、第一层判定。
- **LLM 参与**　无需通用 LLM。按坐标和固定计算规则执行。

## 结果解读

在已有结构叠合的基础上衡量功能位点的空间几何保持程度。FSM 是 MAESD 在筛选第一层使用的局部量。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时子模块。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **TM-align 的原始出处**　[Zhang & Skolnick (2005), TM-align: a protein structure alignment algorithm based on the TM-score](<https://doi.org/10.1093/nar/gki524>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　子角色和 FSM 实现出自 MAESD。叠合算法来自 TM-align。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [TM-align](../../%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/TM-align/TM-align.md)
