# Biopython

[工具接口与执行](../../README.md) / 计算环境与软件库

## 用途

提供读写、转换和处理生物序列、结构与注释的 Python 接口。可充当结构分析流程中的文件解析和数据组织层。

## 输入、输出与 LLM 参与

- **输入**　FASTA、PDB、mmCIF 等生物信息文件，或由调用者传入的序列与结构对象。
- **输出**　可供程序操作的序列、结构和比对对象，或重新导出的数据文件。
- **LLM 参与**　软件库自身无需 LLM。具体算法或外部工具取决于调用的子模块。

## 结果解读

例如结合 DSSP 时，Biopython 可以负责调用和解析结果，二级结构分类规则来自 DSSP。

## 在六篇研究中的用法

使用此来源的研究组件包括 [ProtAgents 二级结构组成统计](../../../04%20%E7%A7%91%E5%AD%A6%E6%A8%A1%E5%9E%8B%E4%B8%8E%E8%AE%A1%E7%AE%97/%E7%BB%93%E6%9E%84%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%AF%94%E8%BE%83/ProtAgents%20%E4%BA%8C%E7%BA%A7%E7%BB%93%E6%9E%84%E7%BB%84%E6%88%90%E7%BB%9F%E8%AE%A1/ProtAgents%20%E4%BA%8C%E7%BA%A7%E7%BB%93%E6%9E%84%E7%BB%84%E6%88%90%E7%BB%9F%E8%AE%A1.md)。

## 原始来源与 GitHub

- **原始论文或方法出处**　[Cock et al. (2009), Biopython: freely available Python tools for computational molecular biology and bioinformatics](<https://doi.org/10.1093/bioinformatics/btp163>)
- **GitHub 仓库**　[biopython/biopython](<https://github.com/biopython/biopython>)
- **归属说明**　原作者软件仓库。

## 下载与访问

- [Biopython 官方下载页](<https://biopython.org/wiki/Download>)　按系统和 Python 环境取得安装文件。
- [仓库源码 ZIP · biopython/biopython](<https://github.com/biopython/biopython/archive/3c32ad9b14d1d52a468d072c1288376f60071d19.zip>)　该仓库的固定快照。
