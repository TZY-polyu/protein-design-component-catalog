# InterPro（项目封装） MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

把 InterProScan 的结构域、家族和功能特征扫描接入 ProteinMCP。

## 输入、输出与 LLM 参与

- **输入**　一条或一批蛋白质序列，通常以 FASTA 文件提供。
- **输出**　各序列中的特征命中、对应位置，以及可映射的 InterPro 功能注释。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

命中表示与已知特征模型相匹配。该项目仓库还提供演示模式，解释结果前应确认所用后端。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/interpro_mcp](<https://github.com/MacromNex/interpro_mcp>)（接口实现）。
- **InterProScan 的原始出处**　[Zdobnov & Apweiler (2001), InterProScan—an integration platform for the signature-recognition methods in InterPro.](<https://doi.org/10.1093/bioinformatics/17.9.847>)
- **InterPro 的原始出处**　[Apweiler et al. (2000), InterPro—an integrated documentation resource for protein families, domains and functional sites](<https://doi.org/10.1093/bioinformatics/16.12.1145>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/interpro_mcp/archive/b66024838cce6a977f61fc51360a2344fd6e029a.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[InterPro](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/InterPro/InterPro.md) · [InterProScan](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/InterProScan/InterProScan.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
