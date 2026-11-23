# MSA MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

让智能体通过服务取得与查询蛋白相关的同源序列比对。

## 输入、输出与 LLM 参与

- **输入**　待查询的一条或多条氨基酸序列。
- **输出**　按比对列排列的查询序列及同源序列。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

比对把潜在对应位点排列在一起。序列数量、覆盖率和缺口分布影响下游进化分析。

## 在六篇研究中的用法

- **ProteinMCP**（案例1使用 MSA MCP）　组织适应度建模所需的比对输入。
- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/msa_mcp](<https://github.com/MacromNex/msa_mcp>)（接口实现）。
- **ColabFold 的原始出处**　[Mirdita et al. (2022), ColabFold: making protein folding accessible to all](<https://doi.org/10.1038/s41592-022-01488-1>)
- **MMseqs2 的原始出处**　[Steinegger & Söding (2017), MMseqs2 enables sensitive protein sequence searching for the analysis of massive data sets](<https://doi.org/10.1038/nbt.3988>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/msa_mcp/archive/93c1d902bd4e19aa0cec32997345209a9636d4d9.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ColabFold](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/ColabFold/ColabFold.md) · [MMseqs2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/MMseqs2/MMseqs2.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
