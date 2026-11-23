# Rosetta

以能量函数和构象采样程序对蛋白质结构进行建模、松弛或打分。

## 输入与输出

- **输入**　三维结构、所选协议及其所需的序列、几何约束或评分设置。
- **输出**　处理后的结构、总分与能量分项，有些协议还返回多个候选及相对排序。

## 接入条件

- **LLM 参与**　能量计算与结构处理无需通用 LLM。
- **运行条件**　按项目说明获取或从源码构建兼容版本。学术等非商业使用受项目许可约束，商业用途需要另行授权。

Rosetta 包含多种协议和评分函数。比较结果时须记录协议、评分函数及所比较的结构。

## 原始来源与公开实现

Simons 等（1999），Ab initio protein structure prediction of CASP III targets using ROSETTA。早期的片段组装方法见下方 1997 年论文。

[论文或原始出版物](https://pubmed.ncbi.nlm.nih.gov/10526365/)

- **GitHub 仓库**　[RosettaCommons/rosetta](https://github.com/RosettaCommons/rosetta)
- **实现入口**　[查看源代码](https://github.com/RosettaCommons/rosetta)

RosettaCommons 官方软件源码。

## 下载

- [下载源码快照（ZIP）](https://github.com/RosettaCommons/rosetta/archive/fc9354ee62a3fdf4d91a294e25b95203d791af83.zip)　该链接固定到仓库中的一个提交。
- [Rosetta 官方软件下载](https://rosettacommons.org/software/download/)　官方发布、源码及使用许可。
- [早期片段组装方法论文（1997）](https://doi.org/10.1006/jmbi.1997.0959)　Simons 等，Assembly of protein tertiary structures from fragments with similar local sequences using simulated annealing and Bayesian scoring functions。
