# AlphaFold2 MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

把蛋白质折叠预测包装为可供研究工作流调用的计算服务。

## 输入、输出与 LLM 参与

- **输入**　单条蛋白质的氨基酸序列，或由多条序列构成的链组。
- **输出**　三维坐标模型及配套的置信度信息，按所用预测模式返回。
- **LLM 参与**　科学计算本身无需通用 LLM。论文中的上层智能体可通过 MCP 请求该计算并解释返回结果。

## 结果解读

坐标表达模型对构象的预测。局部置信度可辅助判断哪些区域的预测较可靠。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的项目自研 MCP 服务（同期注册表）

## 原始来源与 GitHub

- **接口出处**　[ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>) 描述了该服务体系。[同期服务注册记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)
- **GitHub 仓库**　[MacromNex/alphafold2_mcp](<https://github.com/MacromNex/alphafold2_mcp>)（接口实现）。
- **AlphaFold2 的原始出处**　[Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.](<https://doi.org/10.1038/s41586-021-03819-2>)
- **AlphaFold-Multimer 的原始出处**　[Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer](<https://doi.org/10.1101/2021.10.04.463034>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/MacromNex/alphafold2_mcp/archive/68030065ecc279d8c6fd2cff7e1efe3640b9d291.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/src/mcp/configs/mcps.yaml>)　固定提交中的注册表或社区服务目录。

## 关联组件

[AlphaFold-Multimer](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold-Multimer/AlphaFold-Multimer.md) · [AlphaFold2](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
