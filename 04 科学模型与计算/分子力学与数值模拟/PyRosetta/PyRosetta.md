# PyRosetta

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

在 Python 中调用 Rosetta 的结构对象、打分函数和结构操作，供评测或模型分析程序组合使用。

## 输入、输出与 LLM 参与

- **输入**　分子三维坐标、待分析的链或残基，以及所选 Rosetta 评分或结构操作。
- **输出**　Rosetta 评分及其分项、界面几何或经处理的三维构象，取决于调用内容。
- **LLM 参与**　无需通用 LLM。Python 接口执行 Rosetta 的数值模型。

## 结果解读

同一结构在不同评分函数下可获得不同数值。解释时应保留函数名称和计算条件。

## 在六篇研究中的用法

- **BioDesignBench**（运行时／物理评分）　物理打分、结构松弛、固定骨架设计和界面分解均有 PyRosetta 注册接口。补充A.5还用它作界面复核。

使用此来源的研究组件包括 [BioDesignBench 结构质量独立复算](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Chaudhury et al. (2010), PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta](<https://doi.org/10.1093/bioinformatics/btq007>)
- **GitHub 仓库**　[RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta>)
- **归属说明**　Rosetta 官方主仓库内的 Python 绑定。

## 下载与访问

- [官方 PyRosetta 发行包](<https://www.pyrosetta.org/downloads>)　依操作系统和 Python 版本选择。下载页说明非商业与商业授权。
- [仓库源码 ZIP · RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip>)　该仓库的固定快照。

## 关联组件

[Rosetta](../Rosetta/Rosetta.md) · [rosetta_design](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_design/rosetta_design.md) · [rosetta_interface_score](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_interface_score/rosetta_interface_score.md) · [rosetta_relax](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_relax/rosetta_relax.md) · [rosetta_score](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_score/rosetta_score.md)
