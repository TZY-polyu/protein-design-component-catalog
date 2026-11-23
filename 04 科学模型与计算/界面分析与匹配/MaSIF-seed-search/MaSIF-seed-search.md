# MaSIF-seed-search

[科学模型与计算](../../README.md) / 界面分析与匹配

## 用途

比较蛋白表面局部区域的几何与化学特征，寻找可能互补的蛋白片段或种子。

## 输入、输出与 LLM 参与

- **输入**　蛋白三维表面的指定区域、学习得到的表面描述符，以及供比较的种子库。
- **输出**　候选表面匹配、相应片段与几何对应关系，可用于后续结构层面的比较。
- **LLM 参与**　使用专用表面几何模型和检索算法，无需通用 LLM。

## 结果解读

原方法名 MaSIF-seed，AutoBinder 将其检索环节称为 MaSIF-seed-search。匹配分数描述表面互补性，结合能力仍需独立评估。

## 在六篇研究中的用法

- **AutoBinder Agent**（已整合的科学模块）　按表面匹配检索候选片段。

使用此来源的研究组件包括 [AutoBinder 候选种子库](../../../03%20%E6%95%B0%E6%8D%AE%E4%B8%8E%E7%9F%A5%E8%AF%86/%E6%96%87%E7%8C%AE%E4%B8%8E%E7%A0%94%E7%A9%B6%E6%95%B0%E6%8D%AE/AutoBinder%20%E5%80%99%E9%80%89%E7%A7%8D%E5%AD%90%E5%BA%93/AutoBinder%20%E5%80%99%E9%80%89%E7%A7%8D%E5%AD%90%E5%BA%93.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Gainza et al. (2023), De novo design of protein interactions with learned surface fingerprints](<https://doi.org/10.1038/s41586-023-05993-x>)
- **GitHub 仓库**　[LPDI-EPFL/masif_seed](<https://github.com/LPDI-EPFL/masif_seed>)
- **归属说明**　原文称 MaSIF-seed。MaSIF-neosurf 是后续蛋白–配体系统扩展，AutoBinder 未报告使用。

## 下载与访问

- [原作者配套数据](<https://zenodo.org/records/7643697>)　记录提供论文的骨架数据库下载。AutoBinder 自身使用的候选库没有列出版本。
- [仓库源码 ZIP · LPDI-EPFL/masif_seed](<https://github.com/LPDI-EPFL/masif_seed/archive/77153911d8252d02193a6d1d6d0539bf02c5faba.zip>)　该仓库的固定快照。

## 关联组件

[AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
