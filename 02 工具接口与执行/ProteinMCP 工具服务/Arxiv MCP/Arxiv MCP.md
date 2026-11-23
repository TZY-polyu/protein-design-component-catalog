# Arxiv MCP

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

通过 arXiv 查找论文并取得可访问的预印本文本或文件。

## 输入、输出与 LLM 参与

- **输入**　检索词、作者、主题等条件，或已知 arXiv 编号。
- **输出**　论文题名、作者、摘要、版本和对应全文入口或文本。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

同一编号可有多个修订版。引用具体论述时应保留所读的版本。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　检索预印本。
- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [blazickjp/arxiv-mcp-server](<https://github.com/blazickjp/arxiv-mcp-server>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[blazickjp/arxiv-mcp-server](<https://github.com/blazickjp/arxiv-mcp-server>)（接口实现）。
- **arXiv 的原始出处**　[Ginsparg (1994), First steps towards electronic research communication](<https://doi.org/10.1063/1.4823313>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/blazickjp/arxiv-mcp-server/archive/aeb82ecf0e3d6e44d6d1b0341aaef35be5d19df1.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[arXiv](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/arXiv/arXiv.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
