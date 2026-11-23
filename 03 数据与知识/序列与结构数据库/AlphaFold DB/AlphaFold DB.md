# AlphaFold DB

[数据与知识](../../README.md) / 序列与结构数据库

## 用途

通过已知蛋白标识检索预计算的 AlphaFold 预测结构，给分析工具提供模型和置信度文件。

## 输入、输出与 LLM 参与

- **输入**　UniProt 标识符、蛋白名称或批量下载集合。
- **输出**　预测坐标文件、逐残基置信度，以及条目提供的预测对齐误差等数据。
- **LLM 参与**　检索现有数据库条目无需运行 LLM，也无需重新运行 AlphaFold。

## 结果解读

数据库条目是已有预测。研究者提交一个新的序列或自定义复合物做推理，属于预测模型的功能。

## 在六篇研究中的用法

- **ProteinMCP**（架构目录。输入输出按功能归纳）　取得预先计算的结构预测记录。
- **Latent-Y**（平台可用／知识检索）　作者列作结构资料来源。数据库访问与重新运行 AlphaFold 为两种功能。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Varadi et al. (2022), AlphaFold Protein Structure Database: massively expanding the structural coverage of protein-sequence space with high-accuracy models](<https://doi.org/10.1093/nar/gkab1061>)
- **GitHub 仓库**　[google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold/tree/main/afdb>)
- **归属说明**　官方数据库访问示例与说明。数据由 AlphaFold DB 提供。

## 下载与访问

- [结构和置信度文件的批量下载](<https://alphafold.ebi.ac.uk/download>)　EMBL-EBI 官方按数据集合提供文件，并说明版本和格式。
- [仓库源码 ZIP · google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold DB MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/AlphaFold%20DB%20MCP/AlphaFold%20DB%20MCP.md)
