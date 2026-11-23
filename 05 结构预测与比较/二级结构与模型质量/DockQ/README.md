# DockQ

把界面接触恢复情况与界面或配体坐标偏差综合为对接质量分数，比较预测复合物和参照结构。

## 输入与输出

- **输入**　模型复合物、参考复合物，以及需要比较的链或界面对应关系。
- **输出**　取值 0 至 1 的 DockQ 分数，程序还可报告组成该分数的几何或接触指标。

## 接入条件

- **LLM 参与**　无需通用 LLM。
- **运行条件**　需要与操作系统匹配的 DockQ Python 安装包或源码构建环境，并提供可解析的模型和参照结构。

DockQ 衡量模型与特定参考构象之间的界面一致性。分数依赖所用参考结构和链对应关系。

## 原始来源与公开实现

Basu & Wallner (2016), DockQ: A Quality Measure for Protein-Protein Docking Models, PLOS ONE.

[论文或原始出版物](https://doi.org/10.1371/journal.pone.0161879)

- **GitHub 仓库**　[wallnerlab/DockQ](https://github.com/wallnerlab/DockQ)
- **实现入口**　[查看源代码](https://github.com/wallnerlab/DockQ)

Wallner Lab 维护的作者实现，后续版本支持多界面计算。

## 下载

- [DockQ 软件包下载](https://pypi.org/project/dockq/#files)　项目发布的 Python 安装包与源码分发包。
- [项目源码 ZIP](https://github.com/wallnerlab/DockQ/archive/75db7ab4f6b824c70d120c5f620582e164ed5479.zip)　公开项目的源码快照。
