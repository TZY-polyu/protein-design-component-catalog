# ProteinMPNN MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

提交 ProteinMPNN 的逆折叠任务，为给定骨架生成相容的氨基酸序列。

## 输入、输出与 LLM 参与

- **输入**　蛋白质骨架三维坐标和所需的结构上下文。
- **输出**　一个或多个适配该骨架的候选序列及适用的模型评分。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

多个序列可能与同一骨架相容。模型评分描述序列选择，不能直接证明实际折叠或功能。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/proteinmpnn_mcp](<https://github.com/MacromNex/proteinmpnn_mcp>)（接口实现）。
- **ProteinMPNN 的原始出处**　[Dauparas et al. (2022), Robust deep learning–based protein sequence design using ProteinMPNN](<https://doi.org/10.1126/science.add2187>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/proteinmpnn_mcp/archive/771996b9335cac17e0cbea9454c240389a0451ac.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [ProteinMPNN](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/ProteinMPNN/ProteinMPNN.md)
