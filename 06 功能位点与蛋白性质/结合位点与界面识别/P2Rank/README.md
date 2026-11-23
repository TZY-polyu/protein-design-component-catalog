# P2Rank

在蛋白质三维结构表面寻找可能与小分子结合的口袋，并为候选位置排序。

## 输入与输出

- **输入**　蛋白结构原子坐标，通常来自 PDB 或其他受支持的结构文件。
- **输出**　候选口袋的中心、相关残基及预测分数或排名。

## 接入条件

- **LLM 参与**　使用针对口袋识别训练的专用模型，无需通用 LLM。
- **运行条件**　兼容的 Java 运行时和 P2Rank 发行包。仓库与发行包包含训练好的模型。

预测回答的是哪里可能形成配体结合口袋。并不直接给出特定配体的结合构象或实测亲和力。

## 原始来源与公开实现

Krivák & Hoksza (2018), P2Rank: machine learning based tool for rapid and accurate prediction of ligand binding sites from protein structure

[论文或原始出版物](https://doi.org/10.1186/s13321-018-0285-8)

- **GitHub 仓库**　[rdk/p2rank](https://github.com/rdk/p2rank)
- **实现入口**　[查看源代码](https://github.com/rdk/p2rank/blob/b9b54b7e49513b665c913cc90fbfa68ec4133521/src/main/groovy/cz/siret/prank/program/P2Rank.groovy)

上游作者仓库

## 下载

- [下载实现源码（ZIP）](https://github.com/rdk/p2rank/archive/b9b54b7e49513b665c913cc90fbfa68ec4133521.zip)　下载完整仓库快照。具体功能的入口见上方实现源码。
- [P2Rank 官方发行包](https://github.com/rdk/p2rank/releases)　发布页列出可执行软件包和版本差异。
