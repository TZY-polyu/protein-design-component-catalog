# ESM-2

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

将蛋白序列编码为上下文相关表示，用于下游回归、变体打分等任务。ESMFold 使用这一类表示支持结构预测。

## 输入、输出与 LLM 参与

- **输入**　氨基酸序列与选定规模的 ESM-2 检查点。
- **输出**　逐位置表示、氨基酸分布或汇聚后的蛋白级向量，随后可交给独立预测头。
- **LLM 参与**　使用蛋白语言模型，不要求通用 LLM。

## 结果解读

ESM-2 的直接产物是序列表示和分布。要得到三维坐标还需结构预测模块。不同规模的权重对应不同模型。

## 在六篇研究中的用法

- **ProteinMCP**（案例1表征提取）　用两个规模的 ESM-2 模型比较适应度预测特征。
- **BioDesignBench**（运行时／序列设计）　支持序列优化和稳定性评分。补充D还计算 ESM-2 困惑度作独立核对。

使用此来源的研究组件包括 [BioDesignBench 三类质量指标交叉核验](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C/BioDesignBench%20%E4%B8%89%E7%B1%BB%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87%E4%BA%A4%E5%8F%89%E6%A0%B8%E9%AA%8C.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Lin et al. (2023), Evolutionary-scale prediction of atomic-level protein structure with a language model](<https://doi.org/10.1126/science.ade2574>)
- **GitHub 仓库**　[Biohub/esm-archive](<https://github.com/Biohub/esm-archive>)
- **归属说明**　专用蛋白语言模型，与基于它的结构预测器 ESMFold 共用论文和官方代码归档。

## 下载与访问

- [ESM-2 650M 模型权重](<https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t33_650M_UR50D.pt>)　官方目录中的 650M 检查点。
- [ESM-2 3B 模型权重](<https://dl.fbaipublicfiles.com/fair-esm/models/esm2_t36_3B_UR50D.pt>)　官方目录中的 3B 检查点。
- [仓库源码 ZIP · Biohub/esm-archive](<https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip>)　该仓库的固定快照。

## 关联组件

[ESM MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ESM%20MCP/ESM%20MCP.md) · [ESMFold MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ESMFold%20MCP/ESMFold%20MCP.md) · [optimize_sequence](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/optimize_sequence/optimize_sequence.md) · [score_stability](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/BioDesignBench%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3/score_stability/score_stability.md)
