# BLOSUM62

[科学模型与计算](../../README.md) / 序列检索与注释

## 用途

给蛋白序列比对提供氨基酸替换分数，反映在相关蛋白片段中观察到的替换偏好。

## 输入、输出与 LLM 参与

- **输入**　一对待比较的氨基酸符号，或比对程序需要评分的一系列残基对。
- **输出**　矩阵中对应残基对的数值，用于累计比对分数。
- **LLM 参与**　固定的查表参数无需 LLM。

## 结果解读

矩阵本身不执行序列搜索，也没有独立的模型权重。使用者还需指定比对算法与缺口评分规则。

## 在六篇研究中的用法

- **MAESD**（运行时反馈）　为迭代中的多样性调节提供数据。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Henikoff & Henikoff (1992). Amino acid substitution matrices from protein blocks.](<https://doi.org/10.1073/pnas.89.22.10915>)
- **GitHub 仓库**　未确认对应的独立官方仓库。
- **归属说明**　BLOSUM62 是替换矩阵。未确认原作者的独立 GitHub 仓库。

## 下载与访问

- [BLOSUM62 矩阵文本](<https://raw.githubusercontent.com/biopython/biopython/master/Bio/Align/substitution_matrices/data/BLOSUM62>)　Biopython 随软件分发的数据副本。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md)
