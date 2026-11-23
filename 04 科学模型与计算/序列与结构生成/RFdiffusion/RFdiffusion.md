# RFdiffusion

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

用扩散式生成模型构建蛋白骨架，为后续结构分析或独立序列建模提供候选三维构象。

## 输入、输出与 LLM 参与

- **输入**　生成任务的结构条件。也支持不指定外部结构模板的骨架采样。
- **输出**　候选蛋白骨架的三维坐标及对应记录。
- **LLM 参与**　使用专用结构扩散模型，无需通用 LLM。

## 结果解读

产生的坐标是模型样本。序列、实验结构与生物学性质需要分别判读。

## 在六篇研究中的用法

- **BioDesignBench**（运行时／生成）　生成供其他工具评估的骨架。
- **Latent-Y**（仅专家背景调查。未列作 Latent-Y 后端）　仅用于说明参与者经验。文中未将这些工具确认为 Latent-Y 的对应运行后端。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Watson et al. (2023), De novo design of protein structure and function with RFdiffusion](<https://doi.org/10.1038/s41586-023-06415-8>)
- **GitHub 仓库**　[RosettaCommons/RFdiffusion](<https://github.com/RosettaCommons/RFdiffusion>)
- **归属说明**　原模型仓库。

## 下载与访问

- [官方模型文件获取说明](<https://github.com/RosettaCommons/RFdiffusion#readme>)　作者在仓库说明中列出权重来源。源码归档与权重分开。
- [仓库源码 ZIP · RosettaCommons/RFdiffusion](<https://github.com/RosettaCommons/RFdiffusion/archive/86507b6538f51fce57b5a72477165f03999ed7ae.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold2](../../%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/AlphaFold2/AlphaFold2.md) · [design_binder](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_binder/design_binder.md) · [design_fold](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_fold/design_fold.md) · [generate_backbone](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/generate_backbone/generate_backbone.md) · [Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [Rosetta](../../%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md)
