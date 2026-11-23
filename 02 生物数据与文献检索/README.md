# 生物数据与文献检索

从公开资源取回文献、结构、实验记录和生物学注释。

[返回功能目录](../README.md)

## 文献与跨库检索

| 组件 | 主要用途 |
| --- | --- |
| [arXiv MCP Server](%E6%96%87%E7%8C%AE%E4%B8%8E%E8%B7%A8%E5%BA%93%E6%A3%80%E7%B4%A2/arXiv%20MCP%20Server/README.md) | 按主题、作者、时间或分类检索 arXiv 预印本，发现适用的方法论文并检查指定版本。需要阅读时可获取相应文稿。 |
| [arXiv Search（预印本检索）](%E6%96%87%E7%8C%AE%E4%B8%8E%E8%B7%A8%E5%BA%93%E6%A3%80%E7%B4%A2/arXiv%20Search%EF%BC%88%E9%A2%84%E5%8D%B0%E6%9C%AC%E6%A3%80%E7%B4%A2%EF%BC%89/README.md) | 为论文元数据建索引，按关键词、标题、作者和学科条件检索预印本。 |
| [GenomOncology BioMCP](%E6%96%87%E7%8C%AE%E4%B8%8E%E8%B7%A8%E5%BA%93%E6%A3%80%E7%B4%A2/GenomOncology%20BioMCP/README.md) | 将多个生物医学数据源的文献、临床和生物标志物等记录统一暴露为可查询的接口。 |
| [LlamaIndex](%E6%96%87%E7%8C%AE%E4%B8%8E%E8%B7%A8%E5%BA%93%E6%A3%80%E7%B4%A2/LlamaIndex/README.md) | 把论文等文档切分为可检索内容，组织索引、检索器和回答生成器，供智能体按问题取回证据。 |
| [PubMed MCP Server](%E6%96%87%E7%8C%AE%E4%B8%8E%E8%B7%A8%E5%BA%93%E6%A3%80%E7%B4%A2/PubMed%20MCP%20Server/README.md) | 使用 NCBI E-utilities 搜索 PubMed，按 PMID 取回题录与摘要，也能尝试获取带有开放全文的文稿。 |

## 结构与序列数据获取

| 组件 | 主要用途 |
| --- | --- |
| [BioMCP（acashmoney）](%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/BioMCP%EF%BC%88acashmoney%EF%BC%89/README.md) | 通过 MCP 查询 RCSB PDB 中的结构、已记录的位点和配体信息，也可按疾病或研究主题检索相关结构。 |
| [NCBI Datasets 命令行客户端](%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/NCBI%20Datasets%20%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%AE%A2%E6%88%B7%E7%AB%AF/README.md) | 按生物分类或数据库标识检索 NCBI 数据资源，并把序列、注释及元数据打包供本地分析。 |
| [rcsb-api（RCSB PDB 检索客户端）](%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/rcsb-api%EF%BC%88RCSB%20PDB%20%E6%A3%80%E7%B4%A2%E5%AE%A2%E6%88%B7%E7%AB%AF%EF%BC%89/README.md) | 从 Python 查询 RCSB PDB 的结构标识符和元数据，可把数据库检索纳入数据处理脚本。 |

## 分子、通路与组织数据获取

| 组件 | 主要用途 |
| --- | --- |
| [ChEMBL 数据服务](%E5%88%86%E5%AD%90%E3%80%81%E9%80%9A%E8%B7%AF%E4%B8%8E%E7%BB%84%E7%BB%87%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/ChEMBL%20%E6%95%B0%E6%8D%AE%E6%9C%8D%E5%8A%A1/README.md) | 以程序化方式查询 ChEMBL 的化合物、靶标、测定及生物活性记录。 |
| [Open Targets Platform MCP](%E5%88%86%E5%AD%90%E3%80%81%E9%80%9A%E8%B7%AF%E4%B8%8E%E7%BB%84%E7%BB%87%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/Open%20Targets%20Platform%20MCP/README.md) | 通过官方客户端检索 Open Targets 中的基因、疾病和药物条目，并查询平台所收录的关联证据。适合需要标准化标识符或将证据引入分析程序的任务。 |
| [STRINGdb](%E5%88%86%E5%AD%90%E3%80%81%E9%80%9A%E8%B7%AF%E4%B8%8E%E7%BB%84%E7%BB%87%E6%95%B0%E6%8D%AE%E8%8E%B7%E5%8F%96/STRINGdb/README.md) | 在 R 中把蛋白编号映射到 STRING 标识，查询指定物种的蛋白功能关联网络和富集结果。 |
