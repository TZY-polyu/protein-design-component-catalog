# NetMHCpan MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

将 NetMHCpan 的肽与 MHC I 类分子结合相关预测提供给上层工作流。

## 输入、输出与 LLM 参与

- **输入**　肽序列及 MHC I 类分子标识。
- **输出**　适用于该组合的模型预测值和相对排名。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

比较时应留意等位基因、模型版本和输出类型。该服务与 II 类分子预测器采用不同模型。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/netmhcpan_mcp](<https://github.com/MacromNex/netmhcpan_mcp>)（接口实现）。
- **NetMHCpan 的原始出处**　[Nielsen et al. (2007), NetMHCpan, a Method for Quantitative Predictions of Peptide Binding to Any HLA-A and -B Locus Protein of Known Sequence](<https://doi.org/10.1371/journal.pone.0000796>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/netmhcpan_mcp/archive/d9e0c8ecad22a2adc7bb20ee3ca87f6666cb2911.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[NetMHCpan](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E6%80%A7%E8%B4%A8%E4%B8%8E%E5%8A%9F%E8%83%BD%E9%A2%84%E6%B5%8B/NetMHCpan/NetMHCpan.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
