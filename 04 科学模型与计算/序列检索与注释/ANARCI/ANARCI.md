# ANARCI

[科学模型与计算](../../README.md) / 序列检索与注释

## 用途

识别免疫受体可变区，把残基映射到指定编号体系，使不同长度或有插入的序列可按相应位置比较。

## 输入、输出与 LLM 参与

- **输入**　抗体或 T 细胞受体的氨基酸序列及编号体系。
- **输出**　识别出的可变区、链类型、残基位置编号（含插入码）及其对应关系。
- **LLM 参与**　原版 ANARCI 使用序列比对和隐马尔可夫模型，无需通用 LLM。

## 结果解读

结果是位置标注。不同编号体系给出的边界与编号可能不同，读取结果时应同时记录体系名称。

## 在六篇研究中的用法

- **Latent-Y**（平台可用／序列注释）　统一抗体编号，辅助比较序列位置。方法列入工具库，单次调用未逐项披露。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Dunbar & Deane (2016), ANARCI: antigen receptor numbering and receptor classification](<https://pubmed.ncbi.nlm.nih.gov/26424857/>)
- **GitHub 仓库**　[oxpig/ANARCI](<https://github.com/oxpig/ANARCI>)
- **归属说明**　所引原版工具。后续 ANARCII 是不同模型。

## 下载与访问

- [仓库源码 ZIP · oxpig/ANARCI](<https://github.com/oxpig/ANARCI/archive/79f6c575056dedef86cb8f405ebb039197923eec.zip>)　该仓库的固定快照。
