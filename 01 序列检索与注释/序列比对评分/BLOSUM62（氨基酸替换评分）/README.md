# BLOSUM62（氨基酸替换评分）

给蛋白序列比对提供氨基酸替换分数，反映在相关蛋白片段中观察到的替换偏好。

## 输入与输出

- **输入**　一对待比较的氨基酸符号，或比对程序需要评分的一系列残基对。
- **输出**　矩阵中对应残基对的数值，用于累计比对分数。

## 接入条件

- **LLM 参与**　固定的查表参数无需 LLM。
- **运行条件**　按代码使用需要 Python 和 scikit-bio。使用其他比对程序时，可载入与其格式兼容的矩阵文本。

矩阵本身不执行序列搜索，也没有独立的模型权重。使用者还需指定比对算法与缺口评分规则。

## 原始来源与公开实现

Henikoff & Henikoff (1992). Amino acid substitution matrices from protein blocks.

[论文或原始出版物](https://doi.org/10.1073/pnas.89.22.10915)

- **GitHub 仓库**　[scikit-bio/scikit-bio](https://github.com/scikit-bio/scikit-bio)
- **实现入口**　[查看源代码](https://github.com/scikit-bio/scikit-bio/blob/main/skbio/sequence/_substitution.py)

scikit-bio 的 SubstitutionMatrix 提供可运行的公开实现，可载入内置 BLOSUM62 并按氨基酸对取分值。

## 下载

- [NCBI 分发的矩阵](https://ftp.ncbi.nlm.nih.gov/blast/matrices/BLOSUM62)　可直接读取的矩阵文本。
- [scikit-bio 安装包](https://pypi.org/project/scikit-bio/#files)　包括替换矩阵的 Python 实现。
- [下载项目源码（ZIP）](https://github.com/scikit-bio/scikit-bio/archive/HEAD.zip)
