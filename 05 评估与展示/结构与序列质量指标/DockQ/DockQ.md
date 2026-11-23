# DockQ

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

把界面接触恢复情况与界面或配体坐标偏差综合为对接质量分数，比较预测复合物和参照结构。

## 输入、输出与 LLM 参与

- **输入**　模型复合物、参考复合物，以及需要比较的链或界面对应关系。
- **输出**　取值 0 至 1 的 DockQ 分数，程序还可报告组成该分数的几何或接触指标。
- **LLM 参与**　无需通用 LLM。

## 结果解读

分数刻画模型与指定参照界面的相似程度。Latent-Y 列有 DockQ，但没有披露评分程序的精确版本。

## 在六篇研究中的用法

- **Latent-Y**（在线计算筛选）　比较候选的结构可信度与几何一致性。这些指标不能直接给出实测亲和力。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Basu & Wallner (2016), DockQ: A Quality Measure for Protein-Protein Docking Models, PLOS ONE.](<https://doi.org/10.1371/journal.pone.0161879>)
- **GitHub 仓库**　[wallnerlab/DockQ](<https://github.com/wallnerlab/DockQ>)
- **归属说明**　原始 DockQ 指标论文。仓库亦包含后续版。Latent-Y 未注明调用版本。

## 下载与访问

- [DockQ 软件包下载](<https://pypi.org/project/dockq/#files>)　项目发布的 Python 安装包与源码分发包。
- [仓库源码 ZIP · wallnerlab/DockQ](<https://github.com/wallnerlab/DockQ/archive/75db7ab4f6b824c70d120c5f620582e164ed5479.zip>)　该仓库的固定快照。

## 关联组件

[complex RMSD](../complex%20RMSD/complex%20RMSD.md) · [ipTM](../ipTM/ipTM.md) · [Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
