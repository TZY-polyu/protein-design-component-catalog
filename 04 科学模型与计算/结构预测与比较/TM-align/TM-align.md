# TM-align

[科学模型与计算](../../README.md) / 结构预测与比较

## 用途

为两种蛋白三维结构寻找残基对应和空间叠合，以 TM-score 衡量折叠层面的结构相似性。

## 输入、输出与 LLM 参与

- **输入**　两个蛋白结构的坐标与所比较的链。
- **输出**　结构对齐、残基对应关系、TM-score，以及对齐范围和 RMSD 等摘要。
- **LLM 参与**　无需 LLM，通过结构比对算法求解。

## 结果解读

归一化使用哪一侧结构的长度会影响报告值。相似度应和对齐长度、覆盖范围一起看。

## 在六篇研究中的用法

- **MAESD**（运行时科学计算。评测共用）　衡量全局结构相似性，并建立局部功能位点比较所需的空间对应。
- **BioDesignBench**（正文列举／注册状态未证实）　正文列举的结构比对工具。补充表S1未列独立 TM-align 接口。

使用此来源的研究组件包括 [MAESD 核心位点匹配 FSM](../../%E5%8A%9F%E8%83%BD%E7%BA%A6%E6%9D%9F%E4%B8%8E%E5%80%99%E9%80%89%E7%AD%9B%E9%80%89/MAESD%20%E6%A0%B8%E5%BF%83%E4%BD%8D%E7%82%B9%E5%8C%B9%E9%85%8D%20FSM/MAESD%20%E6%A0%B8%E5%BF%83%E4%BD%8D%E7%82%B9%E5%8C%B9%E9%85%8D%20FSM.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Zhang & Skolnick (2005), TM-align: a protein structure alignment algorithm based on the TM-score](<https://doi.org/10.1093/nar/gki524>)
- **GitHub 仓库**　[pylelab/USalign](<https://github.com/pylelab/USalign/blob/master/TMalign.cpp>)
- **归属说明**　作者团队现有 C++ 实现。

## 下载与访问

- [作者发布的源码与程序](<https://zhanggroup.org/RNA-align/TMalign/>)　统一比对包提供 TM-align 的 C++ 源码和部分平台可执行文件。
- [仓库源码 ZIP · pylelab/USalign](<https://github.com/pylelab/USalign/archive/23f14ffcf8647f2dc1c0e01043db3a7f3a661c28.zip>)　该仓库的固定快照。

## 关联组件

[MAESD](../../../01%20%E6%99%BA%E8%83%BD%E4%BD%93%E4%B8%8E%E7%BC%96%E6%8E%92/%E7%A0%94%E7%A9%B6%E7%B3%BB%E7%BB%9F%E4%B8%8E%E5%8D%8F%E4%BD%9C%E6%A1%86%E6%9E%B6/MAESD/MAESD.md) · [TM-score](../../../05%20%E8%AF%84%E4%BC%B0%E4%B8%8E%E5%B1%95%E7%A4%BA/%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BA%8F%E5%88%97%E8%B4%A8%E9%87%8F%E6%8C%87%E6%A0%87/TM-score/TM-score.md)
