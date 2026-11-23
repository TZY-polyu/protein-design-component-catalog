# LigandMPNN MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

根据蛋白骨架及其邻近非蛋白原子环境提出相容的序列候选。

## 输入、输出与 LLM 参与

- **输入**　蛋白质结构、骨架坐标和模型可识别的配体等周围原子信息。
- **输出**　针对给定结构环境生成的一个或多个氨基酸序列。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

候选表示模型判断的序列与环境相容性。实际折叠和分子结合各有独立的验证依据。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/ligandmpnn_mcp](<https://github.com/MacromNex/ligandmpnn_mcp>)（接口实现）。
- **LigandMPNN 的原始出处**　[Dauparas et al. (2025), Atomic context-conditioned protein sequence design using LigandMPNN](<https://doi.org/10.1038/s41592-025-02626-1>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/ligandmpnn_mcp/archive/772a389ed01a9421ba11c6207be2dd0a55e8f510.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[LigandMPNN](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/LigandMPNN/LigandMPNN.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
