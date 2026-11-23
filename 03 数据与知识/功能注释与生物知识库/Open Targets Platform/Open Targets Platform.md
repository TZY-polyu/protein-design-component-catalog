# Open Targets Platform

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

整合遗传学、功能注释与药理等证据，便于研究者查询潜在靶点与疾病之间的已知关联。

## 输入、输出与 LLM 参与

- **输入**　靶点、疾病、药物等实体标识，或要批量提取的数据种类与发布版本。
- **输出**　关联记录、证据来源、聚合分数和元数据，可按数据集下载。
- **LLM 参与**　资源检索和现有分数查询无需通用 LLM。

## 结果解读

关联分数归纳平台收录的证据。判断因果关系或临床作用仍需回到具体证据和原始研究。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　查询生物医学关联背景。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Koscielny 等，Open Targets: a platform for therapeutic target identification and validation（2017）](<https://doi.org/10.1093/nar/gkw1055>)
- **GitHub 仓库**　[opentargets/platform-api](<https://github.com/opentargets/platform-api>)
- **归属说明**　GitHub 提供 Open Targets Platform 官方 API 服务端。数据文件由平台单独发布。

## 下载与访问

- [Open Targets 数据下载](<https://platform.opentargets.org/downloads/data>)　可按数据集和版本获取发布文件。
- [EMBL-EBI 数据发布目录](<https://ftp.ebi.ac.uk/pub/databases/opentargets/platform/>)　按平台发行版本组织的批量数据。 此次连接超时，文件下载状态未确认。
- [关联软件源码 ZIP · opentargets/platform-api](<https://github.com/opentargets/platform-api/archive/253d0d5f16512074f7a86f9181663ab6d58de9dc.zip>)　该仓库的固定快照。

## 关联组件

[Open Targets MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/Open%20Targets%20MCP/Open%20Targets%20MCP.md)
