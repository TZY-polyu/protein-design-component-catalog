# AlphaFold2

由蛋白氨基酸序列预测三维折叠，用于给候选序列提供可分析的结构模型。

## 输入与输出

- **输入**　目标氨基酸序列，以及流程生成或提供的多序列比对、可选结构模板。
- **输出**　预测原子坐标，附逐残基 pLDDT。部分模型额外输出 pTM 和预测对齐误差。

## 接入条件

- **LLM 参与**　使用专用结构预测网络。推理无需通用 LLM。
- **运行条件**　需要官方模型参数。完整数据管线还需要序列和模板数据库。 作者的 Google Cloud 权重下载入口在本次核验地点返回 HTTP 403。使用前需确认运行环境可以取得参数。

局部置信度反映模型对结构的把握。对同一条链预测得稳定，并不能单独确认该蛋白的生物学功能。

## 原始来源与公开实现

Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.

[论文或原始出版物](https://doi.org/10.1038/s41586-021-03819-2)

- **GitHub 仓库**　[google-deepmind/alphafold](https://github.com/google-deepmind/alphafold)
- **实现入口**　[查看源代码](https://github.com/google-deepmind/alphafold)

DeepMind 官方实现。复合物版本 AlphaFold-Multimer 另有论文。

## 下载

- [官方模型参数包](https://storage.googleapis.com/alphafold/alphafold_params_2022-12-06.tar)　上游安装脚本指向的单体与多聚体参数归档。序列数据库另行提供。
- [项目源码 ZIP](https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip)　公开项目的源码快照。
