# MAESD 整体构象评分 GCI

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

综合结构特征，检查全局构象是否支持功能位点的可及性。

## 输入、输出与 LLM 参与

- **输入**　候选和参考结构的二级结构、二硫键、跨膜螺旋及口袋特征。
- **输出**　整体构象完整性分数 GCI、第三层判定。
- **LLM 参与**　无需通用 LLM。按指标计算。

## 结果解读

从局部位点扩展到整体结构特征，评估构象是否仍支持相关部位的可及性。GCI 是计算筛选指标。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时子模块。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　角色及 GCI 的组合方式出自 MAESD。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
