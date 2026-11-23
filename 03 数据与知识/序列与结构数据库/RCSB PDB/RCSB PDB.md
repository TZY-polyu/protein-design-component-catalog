# RCSB PDB

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

为全球 PDB 归档的结构条目提供检索、注释展示、数据 API 及坐标下载。

## 输入、输出与 LLM 参与

- **输入**　PDB 条目标识符，或由分子名称、实验条件和其他元数据组成的检索条件。
- **输出**　相符的条目及其元数据、实验来源、原子坐标与可用的生物学组装文件。
- **LLM 参与**　检索、下载和读出数据均无需 LLM。

## 结果解读

RCSB 是 wwPDB 合作伙伴和访问入口。归档坐标有实验方法及质量信息，归档条目与所选生物学组装需区分。

## 在六篇研究中的用法

- **MAESD**（运行时参照。评测数据）　提供结构检验和近邻搜索的参考。框架也允许以预测骨架作为结构参照。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Berman 等 (2000). The Protein Data Bank.](<https://doi.org/10.1093/nar/28.1.235>)
- **GitHub 仓库**　[rcsb/py-rcsb-api](<https://github.com/rcsb/py-rcsb-api>)
- **归属说明**　这是 RCSB 管理下的资源论文。PDB 档案 1971 年已宣布。GitHub 为官方 API 客户端。

## 下载与访问

- [RCSB 批量文件下载](<https://www.rcsb.org/downloads>)　支持按多个 PDB 标识符选择结构及相关文件。
- [文件下载服务说明](<https://www.rcsb.org/docs/programmatic-access/file-download-services>)　区分不对称单元、生物学组装与实验数据。
- [关联软件源码 ZIP · rcsb/py-rcsb-api](<https://github.com/rcsb/py-rcsb-api/archive/215a6f3ef97da6ac14a6370d9b99cd6e23ba610e.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [PDB MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/PDB%20MCP/PDB%20MCP.md) · [Protein Data Bank](../Protein%20Data%20Bank/Protein%20Data%20Bank.md)
