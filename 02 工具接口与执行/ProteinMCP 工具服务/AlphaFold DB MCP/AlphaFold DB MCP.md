# AlphaFold DB MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

从 AlphaFold 数据库取回已经发布的预测结构。

## 输入、输出与 LLM 参与

- **输入**　已知蛋白编号或可匹配到数据库条目的查询条件。
- **输出**　匹配条目的已有结构模型、坐标下载信息及可用的置信度记录。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

条目未收录与模型预测失败含义不同。该查询本身不启动新的折叠计算。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [Augmented-Nature/AlphaFold-MCP-Server](<https://github.com/Augmented-Nature/AlphaFold-MCP-Server>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[Augmented-Nature/AlphaFold-MCP-Server](<https://github.com/Augmented-Nature/AlphaFold-MCP-Server>)（接口实现）。
- **AlphaFold DB 的原始出处**　[Varadi et al. (2022), AlphaFold Protein Structure Database: massively expanding the structural coverage of protein-sequence space with high-accuracy models](<https://doi.org/10.1093/nar/gkab1061>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/Augmented-Nature/AlphaFold-MCP-Server/archive/a4772f3c7639f93b4db7f89214e3f4692c7b8126.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[AlphaFold DB](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/AlphaFold%20DB/AlphaFold%20DB.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
