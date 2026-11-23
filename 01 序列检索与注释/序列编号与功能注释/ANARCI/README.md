# ANARCI

识别免疫受体可变区，把残基映射到指定编号体系，使不同长度或有插入的序列可按相应位置比较。

## 输入与输出

- **输入**　抗体或 T 细胞受体的氨基酸序列及编号体系。
- **输出**　识别出的可变区、链类型、残基位置编号（含插入码）及其对应关系。

## 接入条件

- **LLM 参与**　原版 ANARCI 使用序列比对和隐马尔可夫模型，无需通用 LLM。
- **运行条件**　原版程序依赖 HMMER 和配套隐马尔可夫模型。

结果是位置标注。不同编号体系给出的边界与编号可能不同，读取结果时应同时记录体系名称。

## 原始来源与公开实现

Dunbar & Deane (2016), ANARCI: antigen receptor numbering and receptor classification

[论文或原始出版物](https://pubmed.ncbi.nlm.nih.gov/26424857/)

- **GitHub 仓库**　[oxpig/ANARCI](https://github.com/oxpig/ANARCI)
- **实现入口**　[查看源代码](https://github.com/oxpig/ANARCI)

Oxford Protein Informatics Group 维护的原版 ANARCI。

## 下载

- [项目源码 ZIP](https://github.com/oxpig/ANARCI/archive/79f6c575056dedef86cb8f405ebb039197923eec.zip)　公开项目的源码快照。
