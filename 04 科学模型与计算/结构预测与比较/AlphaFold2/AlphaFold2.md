# AlphaFold2

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

由蛋白氨基酸序列预测三维折叠，用于给候选序列提供可分析的结构模型。

## 输入、输出与 LLM 参与

- **输入**　目标氨基酸序列，以及流程生成或提供的多序列比对、可选结构模板。
- **输出**　预测原子坐标，附逐残基 pLDDT。部分模型额外输出 pTM 和预测对齐误差。
- **LLM 参与**　使用专用结构预测网络。推理无需通用 LLM。

## 结果解读

局部置信度反映模型对结构的把握。对同一条链预测得稳定，并不能单独确认该蛋白的生物学功能。

## 在六篇研究中的用法

- **MAESD**（运行时推理。评测共用）　为结构评分和下一轮结构条件生成提供依据，也是论文报告的主要算力开销。
- **ProteinMCP**（案例2计算复核。架构亦列该模型）　用单体模式重做结构预测，辅助质量复核。
- **BioDesignBench**（运行时／结构预测）　ColabFold/AF2 是容器依赖。补充A.5把 AF2 与 AF2-Multimer 写作独立质量核验工具，与正文及补充D所写的 Boltz-2 并列记录。
- **Latent-Y**（仅专家背景调查。未列作 Latent-Y 后端）　仅用于说明参与者经验。文中未将这些工具确认为 Latent-Y 的对应运行后端。

使用此来源的研究组件包括 [MAESD 结构新颖性与序列多样性评测](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/MAESD%20%E7%BB%93%E6%9E%84%E6%96%B0%E9%A2%96%E6%80%A7%E4%B8%8E%E5%BA%8F%E5%88%97%E5%A4%9A%E6%A0%B7%E6%80%A7%E8%AF%84%E6%B5%8B/MAESD%20%E7%BB%93%E6%9E%84%E6%96%B0%E9%A2%96%E6%80%A7%E4%B8%8E%E5%BA%8F%E5%88%97%E5%A4%9A%E6%A0%B7%E6%80%A7%E8%AF%84%E6%B5%8B.md)、[ProteinMCP 结合蛋白质量与界面展示](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA/ProteinMCP%20%E7%BB%93%E5%90%88%E8%9B%8B%E7%99%BD%E8%B4%A8%E9%87%8F%E4%B8%8E%E7%95%8C%E9%9D%A2%E5%B1%95%E7%A4%BA.md)、[BioDesignBench 结构质量独立复算](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Jumper et al. (2021), Highly accurate protein structure prediction with AlphaFold, Nature.](<https://doi.org/10.1038/s41586-021-03819-2>)
- **GitHub 仓库**　[google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold>)
- **归属说明**　DeepMind 官方实现。复合物版本 AlphaFold-Multimer 另有论文。

## 下载与访问

- [官方模型参数包](<https://storage.googleapis.com/alphafold/alphafold_params_2022-12-06.tar>)　上游安装脚本指向的单体与多聚体参数归档。序列数据库另行提供。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [仓库源码 ZIP · google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold-Multimer](../AlphaFold-Multimer/AlphaFold-Multimer.md) · [AlphaFold2 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/AlphaFold2%20MCP/AlphaFold2%20MCP.md) · [BindCraft](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/BindCraft/BindCraft.md) · [ColabFold](../ColabFold/ColabFold.md) · [design_fold](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/design_fold/design_fold.md) · [Latent-Y](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/Latent-Y/Latent-Y.md) · [MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [predict_structure](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/predict_structure/predict_structure.md) · [RFdiffusion](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/RFdiffusion/RFdiffusion.md) · [Rosetta](../../%E5%88%86%E5%AD%90%E5%8A%9B%E5%AD%A6%E4%B8%8E%E6%95%B0%E5%80%BC%E6%A8%A1%E6%8B%9F/Rosetta/Rosetta.md) · [validate_design](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/validate_design/validate_design.md)
