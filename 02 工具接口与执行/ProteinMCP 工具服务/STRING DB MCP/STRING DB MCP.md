# STRING DB MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

检索 STRING 中已汇集的蛋白功能关联网络。

## 输入、输出与 LLM 参与

- **输入**　物种及其蛋白标识，或一组待查询的蛋白。
- **输出**　与输入相关的网络边、关联分数及可用的证据类别。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

网络边可以来自多种证据渠道。解释为直接物理接触时应核对支持该边的证据类型。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [Augmented-Nature/STRING-db-MCP-Server](<https://github.com/Augmented-Nature/STRING-db-MCP-Server>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[Augmented-Nature/STRING-db-MCP-Server](<https://github.com/Augmented-Nature/STRING-db-MCP-Server>)（接口实现）。
- **STRING 的原始出处**　[Snel et al. (2000), STRING: a web-server to retrieve and display the repeatedly occurring neighbourhood of a gene](<https://doi.org/10.1093/nar/28.18.3442>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/Augmented-Nature/STRING-db-MCP-Server/archive/d619977afbc7f9c50a7f932726b55e53cf6e746d.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [STRING](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/STRING/STRING.md)
