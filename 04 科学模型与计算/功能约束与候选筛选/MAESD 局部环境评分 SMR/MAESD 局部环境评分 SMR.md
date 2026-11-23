# MAESD 局部环境评分 SMR

[科学模型与计算](../../README.md) / 功能约束与候选筛选

## 用途

评估氢键、疏水相互作用及盐桥所代表的局部支撑。

## 输入、输出与 LLM 参与

- **输入**　设计结构与天然参照对应区域的 GROMACS 分子动力学轨迹。
- **输出**　局部非共价相互作用统计、微环境合理性分数 SMR 及第二层判定。
- **LLM 参与**　无需通用 LLM。由分子模拟和统计规则执行。

## 结果解读

评估参考结构与候选在局部相互作用上的保持程度。GROMACS 提供轨迹，SMR 是 MAESD 依据轨迹统计构造的分数。

## 在六篇研究中的用法

该组件记录于 **MAESD**，对应环节为运行时子模块。

## 原始来源与 GitHub

- **该研究中的定义**　[Song et al. (2026), MAESD: A Unified Multi-Agent Evolutionary Framework for Protein Sequence Design](<https://doi.org/10.1021/acs.jcim.5c02580>)
- **GROMACS 的原始出处**　[Berendsen et al. (1995), GROMACS: A message-passing parallel molecular dynamics implementation](<https://doi.org/10.1016/0010-4655(95)00042-E>)
- **GitHub 仓库**　[nnnnnnz/MAESD](<https://github.com/nnnnnnz/MAESD>)（研究项目仓库）。
- **归属说明**　角色与 SMR 指标由 MAESD 定义。作者补充材料明确以 GROMACS 2021 计算轨迹。

## 下载与访问

- [下载 screening.py](<https://raw.githubusercontent.com/nnnnnnz/MAESD/178044d1fcfa9d43e1bfd718863690afa6b3f66b/agents/maesd/screening.py>)　公开框架中的筛选模块，具体执行取决于配置和可用后端。
- [研究项目源码 ZIP](<https://api.github.com/repos/nnnnnnz/MAESD/zipball/178044d1fcfa9d43e1bfd718863690afa6b3f66b>)　整个研究项目的源码快照。

## 关联组件

[GROMACS](../../%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/GROMACS/GROMACS.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
