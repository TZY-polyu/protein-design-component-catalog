# ProteinMCP 适应度交叉验证

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

分别衡量排序预测质量和执行时间。

## 输入、输出与 LLM 参与

- **输入**　模型预测、实测标签和运行记录。
- **输出**　五折交叉验证的 Spearman 相关、预测与实测散点图、回归头比较表、用时图。
- **LLM 参与**　统计及绘图无需通用 LLM。由主智能体安排。

## 结果解读

将预测排序与已有实验标签比较，用 Spearman 相关量化排序一致性。训练和预测耗时单独汇总。

## 在六篇研究中的用法

该组件记录于 **ProteinMCP**，对应环节为案例1评估与可视化。

## 原始来源与 GitHub

- **该研究中的定义**　[Xu et al. (2026), ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering](<https://doi.org/10.64898/2026.03.11.711149>)
- **GitHub 仓库**　[charlesxu90/ProteinMCP](<https://github.com/charlesxu90/ProteinMCP>)（研究项目仓库）。
- **归属说明**　本文适应度案例的汇总评估。五折验证与相关系数为通用方法。

## 下载与访问

- [下载 fitness_modeling.ipynb](<https://raw.githubusercontent.com/charlesxu90/ProteinMCP/f708d415ef03d9da7107046373160a2776cbd5ed/notebooks/fitness_modeling.ipynb>)　作者的案例 notebook，数据与工具依赖以 notebook 说明为准。
- [研究项目源码 ZIP](<https://api.github.com/repos/charlesxu90/ProteinMCP/zipball/f708d415ef03d9da7107046373160a2776cbd5ed>)　整个研究项目的源码快照。
- [下载期刊补充材料（DOCX）](<https://pmc.ncbi.nlm.nih.gov/articles/instance/13140703/bin/PRO-35-e70547-s001.docx>)　期刊附件，含表 S1–S3 的服务和工作流技能目录。
- [PMC 正式版全文与 PDF 入口](<https://pmc.ncbi.nlm.nih.gov/articles/PMC13140703/>)　可在正式发表版页面选择 PDF 或补充文件。

## 关联组件

[ProteinMCP](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/ProteinMCP/ProteinMCP.md) · [Spearman](../../%E7%BB%9F%E8%AE%A1%E4%B8%8E%E6%AF%94%E8%BE%83%E6%96%B9%E6%B3%95/Spearman/Spearman.md)
