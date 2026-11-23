# AlphaFold-Multimer

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

扩展 AlphaFold2 的结构预测能力，对多条蛋白链联合建模，估计复合物中亚基的相对位置。

## 输入、输出与 LLM 参与

- **输入**　按链区分的蛋白序列。系统还可使用配对或非配对的多序列比对及模板。
- **输出**　多链复合物坐标、链内与链间置信度，包括用于判断界面对位可信程度的 ipTM。
- **LLM 参与**　多链专用结构网络完成预测，无需通用对话 LLM。

## 结果解读

与 AlphaFold2 共用程序仓库，但使用多聚体模型参数。链间置信度不会直接给出实验解离常数。

## 在六篇研究中的用法

- **ProteinMCP**（案例2生成）　BindCraft 借用多聚体模式进行骨架设计。
- **BioDesignBench**（运行时／独立复核）　支持 predict_complex。补充A.5亦列为多链体系的独立结构核验方法。

使用此来源的研究组件包括 [BioDesignBench 结构质量独立复算](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97/BioDesignBench%20%E7%BB%93%E6%9E%84%E8%B4%A8%E9%87%8F%E7%8B%AC%E7%AB%8B%E5%A4%8D%E7%AE%97.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Evans et al. (2021), Protein complex prediction with AlphaFold-Multimer](<https://doi.org/10.1101/2021.10.04.463034>)
- **GitHub 仓库**　[google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold>)
- **归属说明**　多聚体模型与 AlphaFold2 共用官方仓库，另有原始方法论文。

## 下载与访问

- [官方模型参数包](<https://storage.googleapis.com/alphafold/alphafold_params_2022-12-06.tar>)　官方分发脚本列出的共享参数归档，含 AlphaFold2 单体与 Multimer 参数。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [仓库源码 ZIP · google-deepmind/alphafold](<https://github.com/google-deepmind/alphafold/archive/c77e5d2a8961d1a353632c462914ff0a32a950f6.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold2 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/AlphaFold2%20MCP/AlphaFold2%20MCP.md) · [BindCraft](../../%E5%BA%8F%E5%88%97%E4%B8%8E%E7%BB%93%E6%9E%84%E7%94%9F%E6%88%90/BindCraft/BindCraft.md) · [predict_complex](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/predict_complex/predict_complex.md)
