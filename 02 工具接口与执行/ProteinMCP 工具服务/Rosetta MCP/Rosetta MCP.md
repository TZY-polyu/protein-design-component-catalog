# Rosetta MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

在统一的工具服务下调用 Rosetta 的结构建模、局部构象处理或物理评分。

## 输入、输出与 LLM 参与

- **输入**　蛋白质结构与待执行的计算任务，部分任务还需序列或结构约束。
- **输出**　按任务返回构象、序列候选、能量分项或总评分。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

Rosetta 分数的定义取决于所用能量函数。不同设置产生的绝对分值不宜直接横向比较。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/rosetta_mcp](<https://github.com/MacromNex/rosetta_mcp>)（接口实现）。
- **Rosetta 的原始出处**　[Simons et al. (1997), Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions.](<https://doi.org/10.1006/jmbi.1997.0959>)
- **Rosetta 的原始出处**　[Simons et al. (1999), Ab initio protein structure prediction of CASP III targets using ROSETTA.](<https://pubmed.ncbi.nlm.nih.gov/10526365/>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/rosetta_mcp/archive/a17e821af1d5b77b7067b3dd93553f4274da82e4.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [Rosetta](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md)
