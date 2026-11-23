# PLMC MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

通过 PLMC 从同源序列的共同变异中估计位点及位点对之间的统计依赖。

## 输入、输出与 LLM 参与

- **输入**　同一蛋白家族的多序列比对。
- **输出**　进化模型的单点与耦合参数，或借助已拟合模型计算的序列统计分数。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

高耦合表示从序列集合推断的依赖。其成因还可能涉及系统发育等因素。

## 在六篇研究中的用法

- **ProteinMCP**（案例1统计建模）　提取序列位点之间的统计耦合。
- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/plmc_mcp](<https://github.com/MacromNex/plmc_mcp>)（接口实现）。
- **PLMC 的原始出处**　[Hopf et al. (2017), Mutation effects predicted from sequence co-variation](<https://doi.org/10.1038/nbt.3769>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/plmc_mcp/archive/fa139852c1adbba646741cdc794022b96e0fa32f.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[PLMC](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E6%80%A7%E8%B4%A8%E4%B8%8E%E5%8A%9F%E8%83%BD%E9%A2%84%E6%B5%8B/PLMC/PLMC.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
