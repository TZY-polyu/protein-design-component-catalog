# AlphaFold3 MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

调用 AlphaFold 3 预测一个含多种生物分子的体系可能形成的整体构象。

## 输入、输出与 LLM 参与

- **输入**　参与预测的分子组成，包括适用的生物大分子序列和配体描述。
- **输出**　预测的复合物原子坐标、模型置信度和相关结果记录。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

解读分子间相对位置时还需查看链间或界面置信度，单链折叠较可靠也可能伴随链间定位不确定。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/alphafold3_mcp](<https://github.com/MacromNex/alphafold3_mcp>)（接口实现）。
- **AlphaFold 3 的原始出处**　[Abramson et al. (2024), Accurate structure prediction of biomolecular interactions with AlphaFold 3](<https://doi.org/10.1038/s41586-024-07487-w>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/alphafold3_mcp/archive/9ed29a468276df18393fe1f823517aa5df0724ba.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[AlphaFold 3](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold%203/AlphaFold%203.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
