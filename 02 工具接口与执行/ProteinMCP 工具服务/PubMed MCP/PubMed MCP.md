# PubMed MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

检索 PubMed 的生物医学文献记录和相关摘要。

## 输入、输出与 LLM 参与

- **输入**　主题词、作者、检索式或已知的 PMID。
- **输出**　论文书目信息、PMID、可用的摘要，以及可用的全文引用。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

PubMed 收录与全文开放是两项不同属性。全文可能由 PMC 或出版方另行提供。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　检索已收录的论文。
- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [JackKuo666/PubMed-MCP-Server](<https://github.com/JackKuo666/PubMed-MCP-Server>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[JackKuo666/PubMed-MCP-Server](<https://github.com/JackKuo666/PubMed-MCP-Server>)（接口实现）。
- **PubMed 的原始出处**　[美国国家医学图书馆 / NCBI：PubMed 于 1996 年上线，1997 年正式提供免费 MEDLINE 访问（资源发布）](<https://pubmed.ncbi.nlm.nih.gov/about/>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/JackKuo666/PubMed-MCP-Server/archive/2a254f418f431e7ee5c161e38c8144890d52c20b.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [PubMed](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/PubMed/PubMed.md)
