# Foldseek

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

在大型结构数据库中快速寻找与查询蛋白有相似三维折叠的条目，用于检索结构邻居。

## 输入、输出与 LLM 参与

- **输入**　查询结构与目标结构数据库，或两组待比较的结构。
- **输出**　按相似性排序的结构命中，以及比对区间、显著性或结构比对分数。
- **LLM 参与**　无需通用 LLM。

## 结果解读

高相似命中提示共享折叠或局部几何模式。是否具有相同生物学功能，还需结合序列、位点及实验信息判断。

## 在六篇研究中的用法

- **MAESD**（仅离线评估）　为案例的后续结构叠合和功能位点比较选取参照。

## 原始来源与 GitHub

- **原始论文或方法出处**　[van Kempen et al. (2024), Fast and accurate protein structure search with Foldseek](<https://doi.org/10.1038/s41587-023-01773-0>)
- **GitHub 仓库**　[steineggerlab/foldseek](<https://github.com/steineggerlab/foldseek>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [Foldseek 发布与预编译程序](<https://github.com/steineggerlab/foldseek/releases>)　按平台下载软件版本。
- [仓库源码 ZIP · steineggerlab/foldseek](<https://github.com/steineggerlab/foldseek/archive/4f5c00ccb5590f08a261b9144fd9a5d28a71fa0e.zip>)　该仓库的固定快照。
