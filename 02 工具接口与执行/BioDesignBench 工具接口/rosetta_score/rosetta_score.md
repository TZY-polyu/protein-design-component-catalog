# rosetta_score

[工具接口与执行](../../README.md) / BioDesignBench 工具接口

## 用途

对给定结构计算 Rosetta 能量函数的总体及局部得分。

## 输入、输出与 LLM 参与

- **输入**　含坐标的蛋白质结构。
- **输出**　结构总评分、各能量项或逐残基贡献。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

模型强调哪些相互作用可由分项反映。绝对数值应结合能量函数和体系大小解释。

## 在六篇研究中的用法

- **BioDesignBench**　表 S1 原子工具，两种模式均可用。

## 原始来源与 GitHub

- **接口定义**　[Benchmarking and behavioral characterization of LLM agents for protein design](<https://doi.org/10.64898/2026.05.06.723381>)。[作者补充材料与工具表 S1](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)
- **GitHub 仓库**　[jasonkim8652/protein-design-mcp](<https://github.com/jasonkim8652/protein-design-mcp/tree/7a45f13d5c7667513f4b3cfc47e472f3209b1be1>)（含该接口的工具包，固定版本）。
- **PyRosetta 的原始出处**　[Chaudhury et al. (2010), PyRosetta: a script-based interface for implementing molecular modeling algorithms using Rosetta](<https://doi.org/10.1093/bioinformatics/btq007>)
- **Rosetta 的原始出处**　[Simons et al. (1997), Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions.](<https://doi.org/10.1006/jmbi.1997.0959>)
- **Rosetta 的原始出处**　[Simons et al. (1999), Ab initio protein structure prediction of CASP III targets using ROSETTA.](<https://pubmed.ncbi.nlm.nih.gov/10526365/>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/jasonkim8652/protein-design-mcp/archive/7a45f13d5c7667513f4b3cfc47e472f3209b1be1.zip>)　下载同期工具包，含本接口及其他已注册接口。
- [作者补充材料 PDF（工具表 S1）](<https://www.biorxiv.org/content/biorxiv/early/2026/05/08/2026.05.06.723381/DC1/embed/media-1.pdf?download=true>)

## 关联组件

[BioDesignBench](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E6%99%BA%E8%83%BD%E4%BD%93%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9F%BA%E7%BA%BF/BioDesignBench/BioDesignBench.md) · [PyRosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/PyRosetta/PyRosetta.md) · [Rosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md)
