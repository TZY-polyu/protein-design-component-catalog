# ESM-1v

[科学模型与计算](../../README.md) / 蛋白语言模型与序列表征

## 用途

用只在序列上预训练的蛋白语言模型比较不同氨基酸在同一位置上的相对相容性，为变体效应评估提供序列证据。

## 输入、输出与 LLM 参与

- **输入**　参考蛋白质序列、待比较的位置和变体序列，以及 ESM-1v 检查点。
- **输出**　残基概率或相对对数似然分数，也可输出序列表征。
- **LLM 参与**　使用专用蛋白语言模型，不需要通用 LLM。

## 结果解读

分数反映预训练语料中的序列偏好，实验可以检验它对特定任务性质的解释力。该家族提供五个不同的已训练检查点。

## 在六篇研究中的用法

- **ProteinMCP**（案例1模型清单。图中未逐项给出五个结果）　图3a将五个 ESM1v 权重列入 ESM 模型对比。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Meier et al. (2021), Language models enable zero-shot prediction of the effects of mutations on protein function](<https://doi.org/10.1101/2021.07.09.450648>)
- **GitHub 仓库**　[facebookresearch/esm](<https://github.com/facebookresearch/esm>)
- **归属说明**　Meta 官方 ESM 共用仓库，ESM-1v 系列有自己的来源论文。

## 下载与访问

- [ESM-1v 第一组权重](<https://dl.fbaipublicfiles.com/fair-esm/models/esm1v_t33_650M_UR90S_1.pt>)　官方目录列出的五个检查点之一。
- [完整 ESM 模型目录](<https://github.com/Biohub/esm-archive#pre-trained-models>)　可核对模型命名与来源。
- [仓库源码 ZIP · facebookresearch/esm](<https://github.com/Biohub/esm-archive/archive/2b369911bb5b4b0dda914521b9475cad1656b2ac.zip>)　该仓库的固定快照。

## 关联组件

[ESM MCP](../../../02%20%E5%B7%A5%E5%85%B7%E6%8E%A5%E5%8F%A3%E4%B8%8E%E6%89%A7%E8%A1%8C/ProteinMCP%20%E5%B7%A5%E5%85%B7%E6%9C%8D%E5%8A%A1/ESM%20MCP/ESM%20MCP.md)
