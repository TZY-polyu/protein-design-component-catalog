# ProteinMCP 适应度案例数据

[数据与知识](../../README.md) / 文献与研究数据

## 用途

为适应度模型提供参考、训练或评估数据。

## 输入、输出与 LLM 参与

- **输入**　野生型序列、变体序列及相应实验适应度。
- **输出**　序列文件和带标签的变体表。
- **LLM 参与**　无需通用 LLM。

## 结果解读

野生型 FASTA 是坐标和序列的参照，CSV 给出变体与对应实验标签。论文用这些已有测量训练或检验模型。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为案例1输入。标签来自已有实验数据。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文案例的输入文件。未提供独立数据集名称。

## 下载与访问

作者说明案例资料可在平台内获得。期刊正式版另附服务与技能总表。本目录的版本口径仍以给定预印本为准。

- [下载 fitness_modeling.ipynb](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/notebooks/fitness_modeling.ipynb>)　作者的案例 notebook，数据与工具依赖以 notebook 说明为准。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [下载期刊补充材料（DOCX）](<https://pmc.ncbi.nlm.nih.gov/articles/instance/13140703/bin/PRO-35-e70547-s001.docx>)　期刊附件，含表 S1–S3 的服务和工作流技能目录。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md)
