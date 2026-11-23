# ProGen2

[科学模型与计算](../../README.md) / 序列与结构生成

## 用途

对氨基酸序列建模，支持自回归生成或按模型似然比较序列，为候选生成提供序列先验。

## 输入、输出与 LLM 参与

- **输入**　序列前缀、待评分的序列，以及任务所选择的模型检查点。
- **输出**　生成的氨基酸序列，或对给定序列的残基条件概率与模型评分。
- **LLM 参与**　ProGen2 本身是蛋白语言模型，可独立于通用对话 LLM 推理。

## 结果解读

序列的模型概率反映它与训练所得统计规律的相容性。功能与折叠需要其他证据判断。

## 在六篇研究中的用法

- **MAESD**（运行时推理。另作实验对照）　在初始生成阶段保留结构域片段并生成连接区域。另作为独立基线。

使用此来源的研究组件包括 [MAESD 序列生成智能体](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E8%A7%92%E8%89%B2%E5%88%86%E5%B7%A5%E4%B8%8E%E5%8D%8F%E4%BD%9C/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93/MAESD%20%E5%BA%8F%E5%88%97%E7%94%9F%E6%88%90%E6%99%BA%E8%83%BD%E4%BD%93.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Nijkamp et al. (2023), ProGen2: Exploring the boundaries of protein language models](<https://doi.org/10.1016/j.cels.2023.10.002>)
- **GitHub 仓库**　[salesforce/progen](<https://github.com/salesforce/progen>)
- **归属说明**　上游作者仓库。

## 下载与访问

- [ProGen2 官方模型权重清单](<https://github.com/salesforce/progen/tree/main/progen2>)　开发者按模型规模列出独立权重归档，与源码分开下载。
- [仓库源码 ZIP · salesforce/progen](<https://github.com/salesforce/progen/archive/c27a419c234a0997923761e1fe7daffcebf0eaf5.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
