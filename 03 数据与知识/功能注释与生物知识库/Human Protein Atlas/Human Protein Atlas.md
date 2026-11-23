# Human Protein Atlas

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

汇集蛋白和基因在组织、细胞等环境中的表达与定位证据，可作为解释研究对象生物学背景的资料源。

## 输入、输出与 LLM 参与

- **输入**　基因名、蛋白标识符，或组织、细胞等筛选条件。
- **输出**　与基因或蛋白条目关联的组织表达、细胞定位、实验图像或可下载表格，具体字段依资源分区而异。
- **LLM 参与**　数据访问无需 LLM。

## 结果解读

不同数据分区采用不同实验技术和处理流程。比较表达量时需要保留数据来源、量纲和注释版本。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　查询表达与定位背景。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Uhlén et al. (2005), A human protein atlas for normal and cancer tissues based on antibody proteomics](<https://doi.org/10.1074/mcp.M500279-MCP200>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　2005 年初版图谱。2015 年发表扩展的组织蛋白图谱。数据库由 proteinatlas.org 分发。

## 下载与访问

- [Human Protein Atlas 数据下载](<https://www.proteinatlas.org/about/download>)　按主题列出 TSV、XML 等数据文件及字段说明。

## 关联组件

[ProteinAtlas MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ProteinAtlas%20MCP/ProteinAtlas%20MCP.md)
