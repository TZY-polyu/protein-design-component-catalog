# P2Rank

[科学模型与计算](../../README.md) / 性质与功能预测

## 用途

在蛋白质三维结构表面寻找可能与小分子结合的口袋，并为候选位置排序。

## 输入、输出与 LLM 参与

- **输入**　蛋白结构原子坐标，通常来自 PDB 或其他受支持的结构文件。
- **输出**　候选口袋的中心、相关残基及预测分数或排名。
- **LLM 参与**　使用针对口袋识别训练的专用模型，无需通用 LLM。

## 结果解读

预测回答的是哪里可能形成配体结合口袋。并不直接给出特定配体的结合构象或实测亲和力。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算）　给位点选择和结构约束提供依据。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Krivák & Hoksza (2018), P2Rank: machine learning based tool for rapid and accurate prediction of ligand binding sites from protein structure](<https://doi.org/10.1186/s13321-018-0285-8>)
- **GitHub 仓库**　[rdk/p2rank](<https://github.com/rdk/p2rank>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [P2Rank 官方发行包](<https://github.com/rdk/p2rank/releases>)　发布页列出可执行软件包和版本差异。
- [仓库源码 ZIP · rdk/p2rank](<https://github.com/rdk/p2rank/archive/b9b54b7e49513b665c913cc90fbfa68ec4133521.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
