# NCBI Datasets

[数据与知识](../../README.md) / 功能注释与生物知识库

## 用途

按生物分类或数据库标识检索 NCBI 数据资源，并把序列、注释及元数据打包供本地分析。

## 输入、输出与 LLM 参与

- **输入**　基因、物种或已提交记录的标识符，以及请求的数据种类。
- **输出**　可下载的数据包，内容可含 FASTA 序列、基因组注释和结构化元数据报告。
- **LLM 参与**　查询与文件打包无需通用 LLM。MCP 客户端可以代为发起请求。

## 结果解读

NCBI Datasets 是 NCBI 的数据分发服务。下载客户端用于取数，资料范围随所选资源和版本而变。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。未指定子库，输入输出按功能归纳）　访问 NCBI 维护的生物学数据。

## 原始来源与 GitHub

- **原始论文或方法出处**　[O’Leary et al. (2024), Exploring and retrieving sequence and metadata for species across the tree of life with NCBI Datasets](<https://doi.org/10.1038/s41597-024-03571-y>)
- **GitHub 仓库**　[ncbi/datasets](<https://github.com/ncbi/datasets>)
- **归属说明**　NCBI Datasets 在 2020 年首次发布。这里给出资源论文和官方工具仓库。P4 图1 的 NCBI Database 对应项目目录的 NCBI Datasets 接口。

## 下载与访问

- [官方命令行工具下载](<https://www.ncbi.nlm.nih.gov/datasets/docs/v2/command-line-tools/download-and-install/>)　页面提供 datasets 与 dataformat 的各平台分发入口。
- [NCBI 数据查询与下载](<https://www.ncbi.nlm.nih.gov/datasets/>)　可查找记录并选取所需的数据包。
- [仓库源码 ZIP · ncbi/datasets](<https://github.com/ncbi/datasets/archive/9d66d2bcb321612e0e03fc1b43cc18f5e75137eb.zip>)　该仓库的固定快照。

## 关联组件

[NCBI Datasets MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/NCBI%20Datasets%20MCP/NCBI%20Datasets%20MCP.md)
