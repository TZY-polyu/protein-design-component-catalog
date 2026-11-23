# BioMCP（acashmoney 结构分析服务）

[工具接口与执行](../../README.md) / ProteinMCP 工具服务

## 用途

acashmoney 的服务把蛋白结构位点资料和疾病相关蛋白的数据库检索接入 MCP。

## 输入、输出与 LLM 参与

- **输入**　结构查询使用 PDB 标识。疾病相关检索使用疾病或医学状况名称。
- **输出**　结构条目的位点资料，或检索得到的相关蛋白清单。
- **LLM 参与**　数据库检索、注释、显示或作业管理按服务实现执行，无需通用 LLM。语言模型可负责理解查询和解释结果。

## 结果解读

这项社区服务的两个入口面向蛋白条目。它的仓库和所支持的查询与 GenomOncology 的 Biomedical MCP 各自独立。

## 在六篇研究中的用法

- **ProteinMCP**　论文整合的社区 MCP 服务（同期正式目录）

## 原始来源与 GitHub

- **接口出处**　社区项目 [acashmoney/bio-mcp](<https://github.com/acashmoney/bio-mcp>) 发布了这个封装。未确认封装自身有单独发表的论文。[ProteinMCP 收录记录](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)
- **GitHub 仓库**　[acashmoney/bio-mcp](<https://github.com/acashmoney/bio-mcp>)（接口实现）。
- **Protein Data Bank 的原始出处**　[Crystallography: Protein Data Bank (1971). Nature New Biology 233, 223.](<https://doi.org/10.1038/newbio233223b0>)

## 下载与访问

- [下载接口源码 ZIP](<https://github.com/acashmoney/bio-mcp/archive/eb153e774fb63efedede77ecca43ccd5021aed5a.zip>)　下载服务封装源码。科学模型参数或数据库需依上游发布方式获取。
- [查看论文时期的服务清单](<https://github.com/charlesxu90/ProteinMCP/blob/f708d415ef03d9da7107046373160a2776cbd5ed/docs/mcps/public-mcps.md>)　固定提交中的注册表或社区服务目录。

## 关联组件

[Protein Data Bank](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E5%BA%93/Protein%20Data%20Bank/Protein%20Data%20Bank.md) · [ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
