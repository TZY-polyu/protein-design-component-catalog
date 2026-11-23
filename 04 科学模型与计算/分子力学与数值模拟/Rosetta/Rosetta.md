# Rosetta

[科学模型与计算](../../README.md) / 分子力学与数值模拟

## 用途

以能量函数和结构采样程序对分子构象进行建模、松弛或打分。六篇资料中用到的具体 Rosetta 功能随研究而异。

## 输入、输出与 LLM 参与

- **输入**　三维结构、所选协议及其所需的序列、几何约束或评分设置。
- **输出**　处理后的结构、总分与能量分项，有些协议还返回多个候选及相对排序。
- **LLM 参与**　能量计算与结构处理无需通用 LLM。

## 结果解读

Rosetta 是软件套件。报告结果时应指明实际协议、评分函数及比较对象，避免把软件名称当作单一物理量。

## 在六篇研究中的用法

- **AutoBinder Agent**（已整合的科学模块）　执行片段嫁接，将局部片段整合进完整骨架。
- **ProteinMCP**（案例2物理评分）　计算界面评分、形状互补性及氢键相关描述量。
- **BioDesignBench**（运行时／物理评分）　物理打分、结构松弛、固定骨架设计和界面分解均有 PyRosetta 注册接口。补充A.5还用它作界面复核。
- **Latent-Y**（仅专家背景调查。未列作 Latent-Y 后端）　仅用于说明参与者经验。文中未将这些工具确认为 Latent-Y 的对应运行后端。

使用此来源的研究组件包括 [ProteinMCP 结合蛋白质量与界面展示](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA/ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA.md)、[BioDesignBench 三类质量指标交叉核验](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Simons et al. (1997), Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions.](<https://doi.org/10.1006/jmbi.1997.0959>)
- **原始论文或方法出处**　[Simons et al. (1999), Ab initio protein structure prediction of CASP III targets using ROSETTA.](<https://pubmed.ncbi.nlm.nih.gov/10526365/>)
- **GitHub 仓库**　[RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta>)
- **归属说明**　分别为早期片段组装方法和具名 ROSETTA 方法论文。仓库为 Rosetta 软件套件。

## 下载与访问

- [Rosetta Commons 软件下载](<https://rosettacommons.org/software/download/>)　汇集套件、许可和不同分发形式的官方入口。
- [仓库源码 ZIP · RosettaCommons/rosetta](<https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold2](../../%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md) · [BindCraft](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/BindCraft/BindCraft.md) · [Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [PyRosetta](../PyRosetta/PyRosetta.md) · [RFdiffusion](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/RFdiffusion/RFdiffusion.md) · [Rosetta MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/Rosetta%20MCP/Rosetta%20MCP.md) · [rosetta_design](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_design/rosetta_design.md) · [rosetta_interface_score](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_interface_score/rosetta_interface_score.md) · [rosetta_relax](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_relax/rosetta_relax.md) · [rosetta_score](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/rosetta_score/rosetta_score.md)
