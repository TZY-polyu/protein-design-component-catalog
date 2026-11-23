# AlphaFold 3

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

根据组成一个体系的分子实体预测三维结构，可在同一次预测中表示蛋白质、核酸、配体等分子。

## 输入、输出与 LLM 参与

- **输入**　参与体系的序列、化学组分描述和链信息。可附带序列比对与结构模板信息。
- **输出**　预测的原子坐标、整体及局部置信度、链间误差估计等结果文件。
- **LLM 参与**　核心为专用结构预测模型，推理不需要通用对话 LLM。

## 结果解读

输入描述的是参与建模的实体。模型给出可能的空间构象，置信度也不能替代实验测得的亲和力。

## 在六篇研究中的用法

- **AutoBinder Agent**（已整合的科学模块）　预测候选的三维结构。摘要描述复合物预测。未报告实验测得的结合验证结果。
- **ProteinMCP**（架构目录。输入输出按功能归纳）　提供复合物结构预测选项。
- **BioDesignBench**（正文列举／注册状态未证实）　正文将其列作预测工具。补充表S1及A.2可确认的后端为 AF2、AF2-Multimer、ESMFold 与 Boltz-2，未列 AF3 接口。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Abramson et al. (2024), Accurate structure prediction of biomolecular interactions with AlphaFold 3](<https://doi.org/10.1038/s41586-024-07487-w>)
- **GitHub 仓库**　[google-deepmind/alphafold3](<https://github.com/google-deepmind/alphafold3>)
- **归属说明**　DeepMind 官方代码。模型参数另有获取与使用条件。

## 下载与访问

- [官方模型参数](<https://storage.googleapis.com/alphafold3/af3.bin.zst>)　Google 发布的标准模型权重压缩文件，与代码分开发放。 此次自动检查返回 HTTP 403，文件下载状态未确认。
- [模型参数使用条款](<https://github.com/google-deepmind/alphafold3/blob/main/WEIGHTS_TERMS_OF_USE.md>)　官方说明列明参数获取来源和用途条件。
- [仓库源码 ZIP · google-deepmind/alphafold3](<https://github.com/google-deepmind/alphafold3/archive/5870e09dd26a1541bd622fbdfa28dd518cc56192.zip>)　该仓库的固定快照。

## 关联组件

[AlphaFold3 MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/AlphaFold3%20MCP/AlphaFold3%20MCP.md) · [AutoBinder Agent](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/AutoBinder%20Agent/AutoBinder%20Agent.md)
