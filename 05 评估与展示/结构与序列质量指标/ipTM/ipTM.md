# ipTM

[评估与展示](../../README.md) / 结构与序列质量指标

## 用途

利用复合物结构预测器内部的对齐误差分布，估计其对链间相对位置的信心。

## 输入、输出与 LLM 参与

- **输入**　预测器产生的残基对对齐误差分布，以及用于识别不同链的链标识。
- **输出**　0 至 1 范围的界面预测 TM 分数，通常更高表示模型更确信链间相对排布。
- **LLM 参与**　指标本身通过数值计算得到，无需通用 LLM。

## 结果解读

ipTM 一般不需要实验参考结构。它反映模型对界面构象的置信度，不能单独作为测得的结合强度。

## 在六篇研究中的用法

- **Latent-Y**（在线计算筛选）　比较候选的结构可信度与几何一致性。这些指标不能直接给出实测亲和力。

使用此来源的研究组件包括 [ProteinMCP 结合蛋白质量与界面展示](../ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA/ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA.md)、[ProteinMCP 纳米抗体质量与结构展示](../ProteinMCP%20%E7%BA%B3%E7%B1%B3%E6%8A%97%E4%BD%93%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%BB%93%E6%9E%84%E5%B1%95%E7%A4%BA/ProteinMCP%20%E7%BA%B3%E7%B1%B3%E6%8A%97%E4%BD%93%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%BB%93%E6%9E%84%E5%B1%95%E7%A4%BA.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer, bioRxiv v1.](<https://www.biorxiv.org/content/10.1101/2021.10.04.463034v1>)
- **GitHub 仓库**　[google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold>)
- **归属说明**　作者将界面置信度命名为 ipTM。仓库为该指标的官方实现，Latent-Y 的评分后端未披露。

## 下载与访问

- [AlphaFold 官方指标实现](<https://github.com/google-deepmind/alphafold/blob/main/alphafold/common/confidence.py>)　可查看产生界面预测 TM 分数的参考实现。
- [仓库源码 ZIP · google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip>)　该仓库的固定快照。

## 关联组件

[complex RMSD](../complex%20RMSD/complex%20RMSD.md) · [DockQ](../DockQ/DockQ.md) · [Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md)
