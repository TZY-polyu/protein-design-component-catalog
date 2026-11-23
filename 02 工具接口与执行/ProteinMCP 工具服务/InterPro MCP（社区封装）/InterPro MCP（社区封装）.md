# InterPro MCP（社区封装）

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

社区版 InterPro MCP 将 InterProScan 的结构域、家族扫描和相关 GO 映射封装为异步服务。

## 输入、输出与 LLM 参与

- **输入**　蛋白质序列 FASTA 文件，以及所需的注释类别。
- **输出**　作业状态，以及执行完成后产生的序列特征命中和可用的功能注释。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

异步任务标识可用来查询后续结果。与 MacromNex 的项目版本共享底层注释工具，但服务实现与仓库各自独立。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [bio-mcp/bio-mcp-interpro](<https://github.com/bio-mcp/bio-mcp-interpro>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[bio-mcp/bio-mcp-interpro](<https://github.com/bio-mcp/bio-mcp-interpro>)（接口实现）。
- **InterProScan 的原始出处**　[Zdobnov & Apweiler (2001), InterProScan—an integration platform for the signature-recognition methods in InterPro.](<https://doi.org/10.1093/bioinformatics/17.9.847>)
- **InterPro 的原始出处**　[Apweiler et al. (2000), InterPro—an integrated documentation resource for protein families, domains and functional sites](<https://doi.org/10.1093/bioinformatics/16.12.1145>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/bio-mcp/bio-mcp-interpro/archive/0377abd226833ca588c03bdaaa5316cf395ca98f.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[InterPro](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%8A%9F%E8%83%BD%E6%B3%A8%E9%87%8A%E4%B8%8E%E7%94%9F%E7%89%A9%E7%9F%A5%E8%AF%86%E5%BA%93/InterPro/InterPro.md) · [InterProScan](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E5%BA%8F%E5%88%97%E6%A3%80%E7%B4%A2%E4%B8%8E%E6%B3%A8%E9%87%8A/InterProScan/InterProScan.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
